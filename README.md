<div class="Box-sc-g0xbh4-0 js-snippet-clipboard-copy-unpositioned DirectoryRichtextContent-module__SharedMarkdownContent--YORdJ" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto">Node.js Sticky Notes API</h1><a id="user-content-nodejs-sticky-notes-api" class="anchor" aria-label="Permalink: Node.js Sticky Notes API" href="#nodejs-sticky-notes-api"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">Sample RESTful API built on top of Node.js and TypeScript to create and manage sticky notes.</p>
<p dir="auto">This application demonstrates the usage of Node.js and TypeScript to build maintainable software, combining modern architecture, libraries, and tools commonly used in everyday development.</p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto">Technologies</h1><a id="user-content-technologies" class="anchor" aria-label="Permalink: Technologies" href="#technologies"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">The API is built using the following technologies and libraries:</p>
<ul dir="auto">
<li><a href="https://www.typescriptlang.org/" rel="nofollow">TypeScript</a> - Syntactic superset of JavaScript which adds static typing.</li>
<li><a href="https://expressjs.com/" rel="nofollow">Express.js</a> - Node.js web framework.</li>
<li><a href="https://www.postgresql.org/" rel="nofollow">PostgreSQL</a> - Relational database to store sticky notes.</li>
<li><a href="https://sequelize.org/" rel="nofollow">Sequelize</a> - Node.js and TypeScript ORM.</li>
<li><a href="https://tsoa-community.github.io/docs/" rel="nofollow">TSOA</a> - to generate Swagger documentation that following OpenAPI standards.</li>
<li><a href="https://www.npmjs.com/package/swagger-ui-express" rel="nofollow">Swagger UI Express</a> - module that allows serving auto-generated Swagger API docs.</li>
<li><a href="https://www.npmjs.com/package/nodemon" rel="nofollow">Nodemon</a> - Tool to run Node.js applications in development mode.</li>
<li><a href="https://eslint.org/" rel="nofollow">ESLint</a> - Tool to analyze and fix problems and syntax in JavaScript and TypeScript applications.</li>
<li><a href="https://www.npmjs.com/package/ts-node" rel="nofollow">ts-node</a> - TypeScript execution and REPL for node.js, with source map and native ESM support.</li>
<li><a href="https://www.npmjs.com/package/bcrypt?activeTab=readme" rel="nofollow">bcrypt</a> - Library to help you hash passwords.</li>
<li><a href="https://www.npmjs.com/package/dotenv" rel="nofollow">dotenv</a> - zero-dependency module that loads environment variables from a <code>.env</code> file.</li>
<li><a href="https://helmetjs.github.io/" rel="nofollow">Helmet.js</a> - Helmet helps secure Express apps by setting HTTP response headers.</li>
<li><a href="https://joi.dev/" rel="nofollow">joi</a> - Schema description language and data validator for JavaScript.</li>
<li><a href="https://www.npmjs.com/package/jsonwebtoken" rel="nofollow">jsonwebtoken</a> - Package that generates JSON web tokens in JavaScript.</li>
<li><a href="https://www.npmjs.com/package/cors" rel="nofollow">cors</a> - Node.js CORS middleware.</li>
</ul>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto">API Design</h1><a id="user-content-api-design" class="anchor" aria-label="Permalink: API Design" href="#api-design"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">The API sends and receives API resources via API endpoints. Each API resource is represented by a class. Data is stored in a PostgreSQL database instance using Sequelize.</p>
<p dir="auto">There are 5 endpoints exposed to manage sticky notes:</p>
<ul dir="auto">
<li>A <code>[POST] /api/notes</code> route to save new sticky notes in the database.</li>
<li>A <code>[PATCH] /api/notes/{id}</code> route to update sticky notes.</li>
<li>A <code>[DELETE] /api/notes/{id}</code> route to remove sticky notes.</li>
<li>A <code>[GET] /api/notes</code> route to query sticky notes.</li>
<li>A <code>[GET] /api/notes/{id}</code> route to retrieve sticky notes by their IDs.</li>
</ul>
<p dir="auto">These routes are protected and you need to generate a JSON Web Token to access them. You can generate tokens using the route <code>[POST] /api/login</code>. To include JSON Web Tokens in HTTP requests, use the <code>Authorization</code> header. The header value should be formatted like this: <code>Bearer json_web_token_here</code>.</p>
<p dir="auto">You can seed a default user to the database by running <code>npm run seed</code> in the <code>src</code> folder. You need to create a <code>.env</code> file and configure it as follows to correctly connect to the database and run the API:</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>PORT=3000
DATABASE_HOST=localhost
DATABASE_USER=postgres
DATABASE_PASSWORD=pa$$word123
DATABASE_NAME=sticky_notes_node
JWT_PRIVATE_KEY=very_long_and_random_key_to_prevent_security_issues
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="PORT=3000
DATABASE_HOST=localhost
DATABASE_USER=postgres
DATABASE_PASSWORD=pa$$word123
DATABASE_NAME=sticky_notes_node
JWT_PRIVATE_KEY=very_long_and_random_key_to_prevent_security_issues" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">You can use the <code>.env.example</code> file as reference. You may need to change the file <code>src/db/config/db-config.json</code> to match the configuration you have in your <code>.env</code> file due to how the Sequelize CLI works.</p>
<p dir="auto">The list route implements a sorting and pagination pattern that I usually apply in both my personal and professional applications. This pattern is highly flexible, allowing API callers to specify a page and number of items to return in a request. It is also possible to use any valid model field for sorting. In the client-side app, I use the pattern to sort sticky notes by creation date.</p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto">How to Run the Application</h1><a id="user-content-how-to-run-the-application" class="anchor" aria-label="Permalink: How to Run the Application" href="#how-to-run-the-application"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">To run the application, open the <code>src</code> folder using the terminal or command prompt and run the following commands:</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>npm install
npm run seed
npm run develop
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="npm install
npm run seed
npm run develop" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">This will synchronize database data and start the application. Navigate to <code>http://localhost:3000/swagger/</code> to see the Swagger documentation.</p>
<p dir="auto">You can create a production build by running <code>npm run build</code>. This command creates a <code>dist</code> folder with production-ready code.</p>
<p dir="auto">If you add more API routes to this application, you will need to update the Swagger specification file. Run <code>npm run swagger-spec</code> to update it.</p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://raw.githubusercontent.com/evgomes/node-notes-api/main/images/swagger-view.png"><img src="https://raw.githubusercontent.com/evgomes/node-notes-api/main/images/swagger-view.png" alt="Swagger View" style="max-width: 100%;"></a></p>
</article></div>
