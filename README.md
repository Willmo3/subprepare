# Subprepare
## About
Subprepare is a utility for preparing submissions in JMU CS 361. It should work with Dr. Kirkpatrick's setup.

## Usage
### Configuration:
In the script, be sure to update `username` to reflect your JMU e-id. 

Additionally, specify where you want to put your working files in the `workroot` variable. This is not the final submission location, but rather, where you're actually going to change the files and push out changes.

#### Configuration example:
If you had the e-id `catmt` and wanted to store your files in `~/classes/cs361/submissions`, edit `username` to `catmt` and `workroot` to:

`/cs/home/stu/$username/classes/cs361/submissions`

inside the script.

### Running:
On stu:
`chmod +x subprepare`

`./subprepare [lab/pa] [assignment name]`

The lab/pa distinction is very important! By default, the script will attempt to place a submission marked `pa` in a team directory, as opposed to the standard submission directory used for labs.

Then, follow the prompts in your terminal to victory!

#### Example executions:
`./subprepare lab lab3-proc`

`./subprepare pa p1`

## Problems
Report them to me, Willmo3. This thing is tiny, so hopefully it's not too broken!
