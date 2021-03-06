# Installing and Configuring SSM Agent on Windows Instances<a name="sysman-install-ssm-win"></a>

SSM Agent is installed by default on Windows Server 2016 instances and instances created from Windows Server 2003\-2012 R2 AMIs published in November 2016 or later\.

Windows AMIs published *before* November 2016 use the EC2Config service to process requests and configure instances\.

Unless you have a specific reason for using the EC2Config service, or an earlier version of SSM Agent, to process Systems Manager requests, we recommend that you download and install the latest version of SSM Agent to each of your Amazon EC2 instances or hybrid instances that are configured for Systems Manager\.

**Note**  
SSM Agent is updated whenever changes are made to Systems Manager and when new capabilities are added\. To ensure that your instances are always running the newest version of SSM Agent, we recommend that you create a State Manager association that automatically updates SSM Agent when a new version is available\. You can also use Run Command to quickly update one or more instances with the latest version\. For more information, see [Automatically Update SSM Agent \(CLI\)](sysman-state-cli.md) \(State Manager\) and [Update SSM Agent by using Run Command](rc-console.md#rc-console-agentexample)\.

To view details about the different versions of SSM Agent, see the [release notes](https://github.com/aws/amazon-ssm-agent/blob/master/RELEASENOTES.md)\.

**Topics**
+ [Install and Configure SSM Agent on Windows Instances](sysman-install-win.md)
+ [View SSM Agent Logs on Windows Instances](sysman-agent-logs-win.md)
+ [Configure SSM Agent to Use a Proxy for Windows Instances](sysman-install-ssm-proxy.md)