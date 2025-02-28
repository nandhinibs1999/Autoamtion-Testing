This script automates the process of downloading test cases from a CSV file, executing them, generating test reports, and optionally sending the report via email.
Downloads test cases from a given URL.

steps:

1. Download CSV File
The script downloads test cases from a given URL and saves them locally.
2. Read Test Cases from CSV
Reads the test cases from the downloaded CSV file.
3. Execute Test Cases
Simulates test execution by randomly assigning "Pass" or "Fail".
4. Save Test Results to CSV
Writes the test results to a new CSV file.
5. Send Email Report (Optional)
Sends an email with the test results attached (disabled by default).
6. Execution Flow
Runs all steps sequentially.

output:

✅ Downloaded test_cases.csv
✅ Test results saved in test_results.csv
📊 Test Execution Summary:
✔ Passed: 7
❌ Failed: 3
📁 Results saved in test_results.csv






