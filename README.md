# Poor-Man-s-IT-LAB
Some codes of Sem 7 IT Lab

Add this to "Web.config" file for the projects with validations
<configuration>
    <appSettings>
        <add 
            key="ValidationSettings:UnobtrusiveValidationMode" 
            value="None" />
    </appSettings>
</configuration>



Add this to "Web.Config" for the projects with Master page:
<system.webServer>
    <directoryBrowse enabled="true" />
</system.webServer>
