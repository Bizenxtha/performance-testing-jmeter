#### Step 1: Create JMeter Test Plan

1. **Download and Install JMeter**: 
   - Visit the [Apache JMeter website](https://jmeter.apache.org/download_jmeter.cgi) and download the latest version of JMeter.
   - Extract the downloaded files to your desired location.

2. **Launch JMeter**:
   - Navigate to the `bin` directory within the extracted JMeter folder.
   - Run the `jmeter.bat` (for Windows) or `jmeter.sh` (for Unix/Linux) file to launch JMeter.

3. **Create Test Plan**:
   - Right-click on "Test Plan" in the left-hand side tree and select "Add" > "Threads (Users)" > "Thread Group".
   - Add samplers (e.g., HTTP Request) to simulate user actions.
   - Configure necessary parameters for each sampler (URL, method, etc.).
   - Add listeners (e.g., View Results Tree, Summary Report) to view test results.

4. **Save Test Plan**:
   - Go to "File" > "Save Test Plan As".
   - Save the test plan with a `.jmx` extension (e.g., `jmeter.jmx`).

#### Step 2: Set up GitHub Repository

1. **Create GitHub Repository**:
   - Create a new repository on GitHub where you'll store your JMeter test plan and CI workflow.

2. **Push JMX File to Repository**:
   - Add your `test_plan.jmx` file to the repository.
   - Commit and push the changes to GitHub.
