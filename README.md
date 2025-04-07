## Internship Dashboard (Steps to Run the Code)

1. **Open Terminal or Command Prompt**  
   - On **Windows**, press `Win + R`, type `cmd`, and hit Enter.  
   - On **Mac/Linux**, open the Terminal app.

2. **Clone the Repository to Your Computer**  
   - Run this command to download the project from GitHub:  
     ```bash
     git clone https://github.com/hina-xl/Internship.git file_destination
     ```  
   - Replace `file_destination` with the location on your computer where you want to store the project.  
     For example:  
     - On **Windows**:  
       ```bash
       git clone https://github.com/hina-xl/Internship.git C:\Users\YourName\Documents\MyProjects\Internship
       ```  
     - On **Mac/Linux**:  
       ```bash
       git clone https://github.com/hina-xl/Internship.git /Users/YourName/Documents/MyProjects/Internship
       ```

3. **Go to the Project Folder**  
   - Use the `cd` command to change to the project folder:  
     ```bash
     cd file_destination/Internship
     ```  
     Replace `file_destination` with the correct path where the project was stored.

4. **Set Up a Virtual Environment (Optional but Recommended)**  
   - **Using Conda** (if you have it installed):
     - Run this command to create an isolated environment with all necessary packages:  
       ```bash
       conda env create -f environment.yml
       ```  
     - Activate the environment:  
       ```bash
       conda activate your-environment-name
       ```
       
5. **Launch Jupyter Notebook**  
   - After setting up everything, run this command to open the Jupyter interface in your browser:  
     ```bash
     jupyter lab
     ```  
   - In the browser, navigate to the `.ipynb` file and open it.
   - In the Jupyter  Interface, go to the top menu bar and click on the ">>"

---

### Summary:

- **Git Clone:** Download the project from GitHub.
- **Set Up Virtual Environment:** (Optional but makes things easier).
- **Install Jupyter:** If needed, install Jupyter to open and interact with the `.ipynb` notebook.
- **Launch Jupyter Notebook:** Open and run the code in the browser.
