## Resumatch: Instantly Compare Your Resume to Job Descriptions

**Resumatch** is a powerful tool that helps you quickly assess how well your resume aligns with specific job descriptions. By comparing your resume's keywords and skills against the job requirements, Resumatch provides you with a clear and informative match percentage.

### Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/nigel1710/Resume_Reviewing_System.git
   ```
2. **Create Virtual Environment:**
   ```bash
   conda create -p Venv python==3.10 -y
   ```

3. **Install Requirements:**
   ```bash
   cd Resumatch
   pip install -r requirements.txt
   ```

4. **Set Up Google API Key:**
   - Obtain a Google Cloud Platform API key and enable the necessary services (e.g., CustomSearch API).
   - Add your API key in the .env file:
     ```
     GOOGLE_API_KEY="Insert Your API Key Here"
     ```

5. **Run the Application:**
   ```bash
   streamlit run app.py
   ```

### Usage

1. **Enter Job Description:** Paste or type the job description you want to compare against.
2. **Upload Your Resume:** Browse and select your resume file.
3. **Get Match Percentage or Review:** Resumatch will analyze your resume and job description, then display the match percentage.

### Features

* **Keyword Matching:** Compares keywords and skills from your resume against the job description.
* **Skill Assessment:** Evaluates the relevance of your skills to the required job qualifications.
* **Match Percentage:** Provides a clear indication of how well your resume aligns with the job.
* **Resume Review:** Provides a review of the uploaded resume with respect to the job description.


