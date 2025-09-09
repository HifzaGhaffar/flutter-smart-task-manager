| ID   | Title             | Steps                                          | Expected                                                   | Priority |
| ---- | ----------------- | ---------------------------------------------- | ---------------------------------------------------------- | -------- |
| TC1  | Add valid task    | Enter "Buy milk" → click Add                   | Task appears; total=1; pending=1                           | P0       |
| TC2  | Reject empty task | Leave input empty → click Add                  | No task added; no crash                                    | P0       |
| TC3  | Trim whitespace   | Enter "  Read  " → Add                         | Task added as "Read" (no leading/trailing spaces)          | P1       |
| TC4  | Toggle complete   | Add "Walk" → click checkbox                    | "Walk" shows as completed; counts update                   | P0       |
| TC5  | Delete task       | Add "Email" → click delete                     | Task removed; counts update                                | P0       |
| TC6  | Filter pending    | Add pending & completed tasks → select Pending | Only pending shown                                         | P1       |
| TC7  | Filter completed  | ... → select Completed                         | Only completed shown                                       | P1       |
| TC8  | Clear completed   | Have completed tasks → press Clear completed   | Completed removed                                          | P1       |
| TC9  | Duplicate tasks   | Add "Buy milk" twice                           | Two separate entries allowed (or specify desired behavior) | P2       |
| TC10 | Persist (future)  | Run on device after implementing storage       | Tasks remain after restart                                 | P2       |
