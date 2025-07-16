# GitHub Actions Demo: Print hello.txt

This is a simple GitHub Actions project that demonstrates how to trigger a workflow when code is pushed to the `mamunBranch` branch. The workflow reads the contents of a file named `hello.txt` and prints it to the Actions log.

## 📁 Files

- `hello.txt`: A plain text file containing a message.
- `.github/workflows/print-hello.yml`: The GitHub Actions workflow that prints `hello.txt`.

## ⚙️ Workflow Details

The GitHub Actions workflow:
- Runs on every push to the `mamunBranch` branch
- Checks out the repository code
- Reads and outputs the contents of `hello.txt`

## 🚀 How to Use

1. Clone the repository.
2. Make sure `hello.txt` is in the root of the `main` branch.
3. Push any changes to the `mamunBranch` branch.
4. Go to the **Actions** tab in GitHub and watch the workflow run.
5. Open the latest workflow run to see the output of `hello.txt`.

## 📦 Example Output


