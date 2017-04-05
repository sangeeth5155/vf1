# vf1
Home page of the task
<apex:page controller="cont2" showHeader="true">
<h1>Welcome</h1>
    <apex:form > <center>
       WELCOME TO THE HOMEPAGE<br/><br/>
        <apex:commandButton action="{!doSignup}" value="Signup"/> <br/><br/><br/>
        <apex:commandButton action="{!doLogin}" value="Login"/> <br/>
        </center>
    </apex:form>
</apex:page>
