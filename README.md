# Writing Good Documentation
## Step 1 - Using Codeblocks
Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good _Cloud Engineer_ uses Codeblocks whenever possible.
Because it allows others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown you need to use three backticks (```) 
- Not to be confused with quotation ('')
```
// Import required modules
const http = require('http');

// Create an HTTP server and listen for requests on port 3000
const server = http.createServer((req, res) => {
  // Set the response header with content type
  res.setHeader('Content-Type', 'text/plain');
  // Write the response body
  res.end('Hello, World!\n');
});

// Start the server and listen on port 3000
server.listen(3000, 'localhost', () => {
  console.log('Server running at http://localhost:3000/');
});
```
- When you can you should attempt to apply syntax highlighting to your codeblocks.
```node.js
// Import required modules
const http = require('http');

// Create an HTTP server and listen for requests on port 3000
const server = http.createServer((req, res) => {
  // Set the response header with content type
  res.setHeader('Content-Type', 'text/plain');
  // Write the response body
  res.end('Hello, World!\n');
});

// Start the server and listen on port 3000
server.listen(3000, 'localhost', () => {
  console.log('Server running at http://localhost:3000/');
});
```
![njs1](https://github.com/Emmy-code-dev/github-docs-example/assets/63400363/6fe81722-7120-4bb8-aca4-52980fb16f48)

Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.
```bash
try {
  // Attempt to access a variable that does not exist
  console.log(nonExistentVariable);
} catch (error) {
  // Catch the error and log it to the console
  console.error('An error occurred:', error.message);
}
```
> Here is an example for using code blocks for an error that appears in bash.

## References
- [Github Flavoured Markdown](https://github.github.com/gfm/)<sup>[1]</sup>
- [Basic writing and formatting syntax(Github Flavoured Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)<sup>[2]</sup>

