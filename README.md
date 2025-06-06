# -Resume-Review-Agentic-System-with-N8N

## Workflow Image
Here is a visual representation of the system:

![Workflow Overview](https://github.com/Ishita95-harvad/build-a-resume-review-agentic-system-with-N8N/blob/main/Create%20a%20workflow%20im.png)


## Description
This project integrates **n8n**, a workflow automation tool, with AI-powered resume analysis. It streamlines the process of reviewing resumes, offering feedback, and recommending job opportunities using an **Agentic System** approach.


# Save the updated workflow to a JSON file
fixed_file_path = "/mnt/data/AI_Resume_Screener_Fixed_Workflow.json"
Path(fixed_file_path).write_text(json.dumps(updated_workflow, indent=2))

fixed_file_path


## Features
- **Automated Resume Parsing**: Extracts key details from resumes (PDF, DOCX).
- **AI-Powered Resume Optimization**: Improves formatting, wording, and relevance.
- **Job Matching & Recommendations**: Suggests relevant job opportunities.
- **n8n Workflow Integration**: Automates resume evaluation.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/build-a-resume-review-agentic-system-with-N8N/resume-review-n8n.git

- Navigate to the project directory:
cd resume-review-n8n
- Install dependencies:
npm install


- Start n8n:
n8n start


### Usage
- Upload your resume via the n8n workflow.
- The AI agents analyze and optimize your resume.
- Receive feedback and job recommendations.
- Iterate improvements and finalize your resume.
### Workflow Overview
The workflow includes:
- Resume Input Node: Accepts resumes for processing.
- AI Analysis Node: Uses NLP and machine learning models.
- Optimization Node: Enhances the resume for better readability and impact.
- Job Recommendation Node: Maps skills to relevant job postings.
### Contributor
- #### Ishita [Lead Developer]

### License
This project is licensed under the MIT License.
