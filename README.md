<h1> Langgraph-workshop-Lumos_SDC  </h1>

This repository has been made in relation to a presentation of mine, which I  held for Lumos Student Data Consulting. 
The presentation was about Langgraph, a framework for building agentic AI applications. 

This repository contains two folders. The folder "demo" showcases an example of a graph that shall work as an financial advisor. The second folder "tryit" contains a simple example of an graph with that works as an try-it-yourself notebook.

<h2> Content </h2>
The <b>demo</b> folder is the contains the code for the demonstration that was performed during the presentation.
<br><br>
The <b>try_it_yourself</b> folder contains a notebook with a graph that has been partially set up. You need to do some small coding tasks in order for the graph to run. 
<h2> Instructions </h1>

Open terminal: 
```bash
git clone https://github.com/DataJakob/Langgraph-workshop-Lumos-SDC.git
```
Buy an openai API key. Create a file named ".env" in repo and add following info:
```bash
OPEN_API_KEY="my_key_value"
```

Create enviroment:
```bash
python -m venv myenv
```

Activate enviroment:
```bash
myenv\Scripts\activate
```

Install requirements:
```bash
pip install -r requirements.txt
```

Choose myenv as kernel in Jupyter notebook and run cells.
