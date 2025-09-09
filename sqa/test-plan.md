Project: Smart Task Manager
Scope: FR1..FR6
Test Types: Manual functional, Unit tests (controller), Widget tests (UI), Regression
Test Tools: DartPad (manual), Flutter test (local), GitHub issues (bugs), Spreadsheet/CSV for results
Test Environments:
  - DartPad (Chrome latest on Windows 10)
  - Local Flutter  stable (when you run locally) + Android Emulator
Entry Criteria:
  - Code in `lib/main.dart` runs in DartPad
Exit Criteria:
  - All P0/P1 test cases pass; no P0 open defects
Risks:
  - Limited package support in DartPad, no device testing there
Schedule: Create → Test case design → Execute manual tests → Add unit tests → Report
