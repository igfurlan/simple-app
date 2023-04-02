<<<<<<< HEAD
This is a simple application, written in GO language. It creates a web host and shows a small message.

The objective of this is to create a Continuous Deployment pipeline.

Most important steps are to build and push a new docker image after the git push command. 
And deploy this into our host.

Some of the steps executed on the host are to:
	1. Kill the current container execution
	2. delete the old docker image
	3. Download and run the newly created image
>>>>>>> 8238fcd (Adding a description on README file)
