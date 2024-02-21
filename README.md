<h1 id="pdf-whisperer">Unlock Conversational PDF Understanding with GPT-3.5-Turbo</h1>

<p>Harness the power of GPT-3.5's language understanding to unlock meaningful insights from your PDFs in a user-friendly Streamlit interface. Summarize, analyze, and extract information effortlessly.</p>

<p>This open-source project, pdf-whisperer, empowers you to have interactive, in-depth conversations with the content of your PDFs. It leverages the cutting-edge language model GPT-3.5-Turbo and the combined strengths of Langchain and Streamlit for a seamless user experience.</p>

<h3>Key Features</h3>

<b>1. Conversational AI</b>: Ask questions and have natural-language conversations about your PDFs.<br>
<b>2. Streamlit Interface</b>: User-friendly interface for uploading PDFs and interacting with the AI.<br>
<b>3. GPT-3.5-Turbo Power</b>: The latest language model from OpenAI provides comprehensive understanding.<br>
<b>4. Langchain Integration</b>: Handles complex information extraction and retrieval from PDFs.<br>
<b>5. Interactive Exploration</b>: Ask follow-up questions, explore specific sections, and search keywords.<br>


<h2>Installation</h2>

<h3>Prerequisites</h3>

<ul>
  <li><strong>Conda: **  Ensure you have conda installed. If not, download and install it from <a href="https://docs.conda.io/projects/conda/en/latest/index.html" target="_blank">https://docs.conda.io/projects/conda/en/latest/index.html</a>.</li>
</ul>

<h3>Steps</h3>

<ol>
  <li>
    <h4>Create a virtual environment:</h4>
    <pre><code>conda create -n pdf-whisperer-env python</code></pre>
    <p>Once created, activate the environment:</p>
    <pre><code>conda activate pdf-whisperer-env</code></pre>
  </li>
  <li>
    <h4>Clone the repository:</h4>
    <pre><code>git clone https://github.com/kunal1704/pdf-whisperer.git</code></pre>
  </li>
  <li>
    <h4>Install dependencies:</h4>
    <pre><code>cd pdf-whisperer && pip install -r requirements.txt</code></pre>
  </li>
  <li>
    <h4>Provide your OpenAI API key:</h4>
    <p>Obtain your OpenAI API key from <a href="https://beta.openai.com/account/api-keys" target="_blank">https://beta.openai.com/account/api-keys</a> and replace the placeholders <code>"<YOUR_API_KEY>"</code> with your actual key in the following lines within <code>app.py</code>:</p>
    <ul>
      <li>Line 15</li>
      <li>Line 31</li>
      <li>Line 44</li>
      <li>Line 51</li>
    </ul>
  </li>
  <li>
    <h4>Run the application:</h4>
    <pre><code>streamlit run app.py</code></pre>
  </li>
</ol>

<h2>Remember</h2>

<ul>
  <li>Replace <code>"<YOUR_API_KEY>"</code> with your actual OpenAI API key in all four places within <code>app.py</code>.</li>
  <li>Ensure you have an active internet connection throughout the process.</li>
</ul>
