# CFE ReactJS

## Getting Started

### **Step 1: Fork the Repository**

1. **What is forking?** Forking creates your own copy of the repository on your GitHub account.
2. **How to fork the repo:**
   - Visit the **CFE ReactJS GitHub repository**.
   - In the top-right corner of the repository page, click the **Fork** button.
   - This will create a copy of the repository in your GitHub account.

#### **Step 2: Clone Your Forked Repository**

1. **What is cloning?** Cloning downloads the repository to your local computer.
2. **How to clone:**

   - Go to your forked repository (on your GitHub profile).
   - Click the **Code** button and copy the HTTPS/SSH link.
   - Open your terminal/command prompt and run the following command:

     ```bash
     git clone <your-forked-repo-url>
     ```

   - Replace `<your-forked-repo-url>` with the URL you copied.

#### **Step 3: Navigate to the Repository**

1. Open a terminal and navigate into the cloned repository directory:

   ```bash
   cd <repository-name>
   ```

   Replace `<repository-name>` with the name of the cloned folder.

#### **Step 4: Create Your Own Folder**

1. Inside the cloned repository, create a folder with **your name**.
2. Run the following command in the terminal:

   ```bash
   mkdir <your-name>
   ```

   Replace `<your-name>` with your name or username.

#### **Step 5: Add a `name.txt` File**

1. Inside the folder you just created, add a `name.txt` file:

   - Run the following command:

     ```bash
     echo "Your Name: <Your Name> | Details: <Your Details>" > <your-name>/name.txt
     ```

     Replace `<Your Name>` and `<Your Details>` with your actual name and any details you'd like to add (e.g., email, username, or fun fact).

#### **Step 6: Stage and Commit Your Changes**

1. **Stage your changes:**

   ```bash
   git add <your-name>
   ```

   Replace `<your-name>` with your folder name.

2. **Commit your changes:**

   ```bash
   git commit -m "Added folder and name.txt for <your-name>"
   ```

   Replace `<your-name>` with your name.

#### **Step 7: Push Changes to Your Fork**

1. Push your changes to your forked repository:

   ```bash
   git push origin main
   ```

   Ensure you’re on the `main` branch (or the default branch used by the repo).

#### **Step 8: Create a Pull Request**

1. Go to your forked repository on GitHub.
2. Click the **Pull Requests** tab.
3. Click **New Pull Request**.
4. Select your forked repository and branch as the source and the original repository as the target.
5. Add a title and description for your pull request, then submit it.
