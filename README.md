# No-Code-Data-Analysis-using-LLMs
An AI-powered Q&amp;A web app using the Mistral model via Ollama, Python backend, and MySQL. Set up virtual env, install dependencies, run MySQL &amp; Ollama, launch app.py, upload data, and ask questions. Results are generated dynamically based on uploaded content or custom queries.


Here's the step by step process:

Step 1 : Create virtual Environment -> python -m venv myenv
	 Activate virtual environment -> myenv\Scripts\activate
	 Install requirements.txt
	 pip install -r requirements.txt

Step 2 : Install and Start MySQL Server
	 Win+R -> type services.msc -> Enter -> Right click on Mysql -> Click "Start" (Windows)
	 sudo apt update -> sudo apt install mysql-server -> sudo systemctl start mysql (Linux)

Step 3 : Install and run Ollama locally in computer and Pull the "mistral" model
	 Go to the official website: https://ollama.com -> Download and install Ollama (Windows)
	 Open cmd -> ollama pull mistral -> ollama run mistral

	 Ollama Install : curl -fsSL https://ollama.com/install.sh | sh (Linux)
	 ollama run mistral 

Step 4 : Run app.py in VSCode
	 Open the localhost website

Step 5 : Upload the "sample_data" file

Step 6 : Ask any question from the question.txt or any other question 

Step 7 : Result is displayed


