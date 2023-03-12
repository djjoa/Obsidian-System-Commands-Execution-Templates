<% 
// Templater required opening tag 
tp. // Templater object 
user. // User Functions
pwsh7_exec({ // Use the "Function Name" pwsh5_exec which maps to Invoke-Expression 
Pwsh: // "Pwsh" part of "$Env:Pwsh" i.e. the argument expected by pwsh5_exec
tp.file.selection() // The command that will be executed / What has been highlighted on the screen
})
// template required closing tag stripping whitespace after inserting output
_%>