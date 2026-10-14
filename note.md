

the tech stack used on the project includes:    

nextjs and typescript for the frontend.
tsmorph parses the code
react flow draw the map
clerk for authentication and user management
supabase for database and storage
langsmith prove the ai is not lying
coderabbit reviewing the code

model and agent difference.
an agent is a program that can perform tasks autonomously, while a model is a representation of data or a system that can be used for analysis or prediction. In the context of AI, an agent can use models to make decisions and take actions based on the information it has.

the flow 


features.md
. what it does
shows what breaks when a file changes
. not allowed
never edits your code
. done when
every file it names really exists
|
|

AGENT
turn into code


OUTPUT
working code

ME 
i check it


9 skiills that you should install to a project.

/scope -idea challenges the idea

/developer   builds it
/checker   checks turns on different models to reviews


claude plugin install frontend-design@claude-plugins-official install it in your project to get a frontend design agent that can help you with UI/UX design tasks. it will standout from other designs.


setup clerk next for auth
after that installed supabase for database and storage. then setup tsmorph to parse the code and react flow to draw the map. finally, integrate langsmith to ensure the AI is providing accurate information and coderabbit to review the code for quality assurance.

supabase mcp is using here to manage the database and storage needs of the project. It provides a seamless integration with the frontend and backend, allowing for efficient data handling and retrieval.

for the claude
claude mcp add --scope project --transport http supabase "https://mcp.supabase.com/mcp?features=docs%2Caccount%2Cdatabase%2Cdebugging%2Cdevelopment%2Cfunctions%2Cbranching"