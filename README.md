# Ora-Pwn
An Oracle attack tool written in PowerShell and using the .NET OracleClient Namespace. Can be used to bruteforce SIDs, user credentials, to execute queries, and inject a UNC path for triggering an NTLM authentication attempt against a provided host.

v1.2 - Now supports Muli-threading!


## Current Functions:
    Invoke-SIDGuess             -   Checks to see if provided SIDs are valid.
    Invoke-CredentialGuess      -   Checks to see if provided Username and Password is valid.
    Invoke-QueryExec            -   Executes and returns output for provided querys
    Invoke-UNCInject-DS         -   Injects a UNC file path and uses the creation of indexes by ctxsys.context

## Future Additions:
    Functions:
    Invoke-UNCInject-TNS        -   Injects UNC path into log_path portion of the TNS connection string
    Invoke-InjectShell          -   Creates a reverse shell.

