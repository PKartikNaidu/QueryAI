<h1>QueryAI</h1>
    <p>QueryAI is a simple chat application integrated with MySQL for querying databases using natural language. It provides a conversational interface for interacting with your MySQL database, enabling users to ask questions and receive SQL-based responses.</p>

 <h2>Features</h2>
    <ul>
        <li>Natural language interface for querying MySQL databases</li>
        <li>Seamless integration with Streamlit for a user-friendly interface</li>
        <li>Support for conversation history to maintain context during interactions</li>
    </ul>
    
  <h2>Getting Started</h2>
    <p>To get started with QueryAI, follow these steps:</p>

  <h3>Prerequisites</h3>
    <ul>
        <li>Python 3.x installed on your system</li>
        <li>MySQL installed and running</li>
        <li>Required Python packages installed (specified in <code>requirements.txt</code>)</li>
    </ul>

<h3>Dataset</h3>
<p>The project can be applied to any SQL database containing tables and records that you want to query using natural language.</p>

<h3>How it Works</h3>
<p>The LLM project leverages natural language processing techniques to convert user input into SQL queries. Here's how it works:    
<ol>
        <li><strong>User Input:</strong> Enter a natural language prompt (e.g., "Show me all customers from New York").</li>
        <li><strong>NLP Processing:</strong> Use NLP libraries to parse and understand the user query.</li>
        <li><strong>SQL Query Generation:</strong> Convert the parsed input into SQL queries that can be executed on the database.</li>
        <li><strong>Database Interaction:</strong> Execute the generated SQL query on the connected SQL server.</li>
        <li><strong>Response:</strong> Display the results back to the user in a readable format.</li>
</ol>

  <h2>Usage</h2>
    <p>Set up your MySQL database configuration by modifying the settings in the sidebar of the application:</p>
    <ul>
        <li>Host</li>
        <li>Port</li>
        <li>User</li>
        <li>Password</li>
        <li>Database</li>
    </ul>
    <p>Click on the "Connect" button to establish a connection to the database.</p>
    <p>Once connected, you can start interacting with QueryAI by typing your queries in the chat input field. QueryAI will interpret your natural language queries, convert them into SQL queries, execute them against the database, and display the results.</p>

   
