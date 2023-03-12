<% 
// Templater required opening tag 
tp. // Templater object 
user. // User Functions
cmd_exec({ // Use the "Function Name" cmd_exec which maps to cmd /C  
Cmd: // Argument expected by cmd_exec i.e. %Cmd%
tp.file.selection() // The command that will be executed / What has been highlighted on the screen
})
// template required closing tag stripping whitespace after inserting output
_%>