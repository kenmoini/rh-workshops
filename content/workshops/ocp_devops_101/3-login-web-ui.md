---
title: Access the OpenShift Web UI
workshops: ocp_devops_101
workshop_weight: 20
layout: lab
---

{{< related_assets style="grey pf-u-mt-0" >}}
  {{< related_asset title="OpenShift Cluster" specialLink="ocpCluster" >}}{{< /related_asset >}}
{{< /related_assets >}}

Red Hat OpenShift provides a Web UI Console that allows you to perform various tasks via a web browser. Additionally, you can utilize a command line tool to perform tasks. Let's get started by logging into both of these and checking the status of the platform.

{{< twoSideStep title="1. Select Identity Provider" >}}
    
    {{< leftStep size="7" >}}
        {{< figureImage src="../img/OCPloginProviders.jpg" title="OpenShift Identity Selection" >}}
    {{< /leftStep >}}

    {{< rightStep size="5" >}}

<p>Red Hat OpenShift provides additional authentication methods out-of-the-box with their offering of Kubernetes.  You can connect multiple identity providers and consume them however you'd like.</p>
{{% markdownify %}}
- Select the <strong>Workshop LDAP</strong> identity provider to continue.
{{% /markdownify %}}
    {{< /rightStep >}}
{{< /twoSideStep >}}

{{< twoSideStep title="2. Log in with Student Credentials" >}}
    
    {{< leftStep size="7" >}}
        {{< figureImage src="../img/ocpLoginPrompt.jpg" title="Enter your credentials" >}}
    {{< /leftStep >}}

    {{< rightStep size="5" >}}

<p>Use the following details to log in:</p>
<ul>
<li><strong>Username:</strong> student{{< studentNumber >}}</li>
<li><strong>Password:</strong> <span class="generatedText workshopPassword studentPassword" data-original-text="Provided by workshop proctor">Provided by workshop proctor</span></li>
</ul>

    
    {{< /rightStep >}}
{{< /twoSideStep >}}

{{< twoSideStep title="3. Successful Authentication" >}}
    
    {{< leftStep size="7" >}}
        {{< figureImage src="../img/ocpInitialLogin.jpg" title="Default view upon log in" >}}
    {{< /leftStep >}}

    {{< rightStep size="5" >}}

<p>Upon logging into Red Hat OpenShift via the Web UI, you'll be greeted with the <strong>Projects</strong> in the <strong>Administrator</strong> view.</p>
<p>It will initially be blank but don't worry, we'll get to deploying some containers shortly.</p>
    {{< /rightStep >}}
{{< /twoSideStep >}}

{{< twoSideStep title="4. Switch to the Developer Console" >}}
    
    {{< leftStep size="7" >}}
        {{< figureImage src="../img/switchToDeveloper.jpg" title="Use the dropdown to switch from the Administator to the Developer Console" >}}
    {{< /leftStep >}}

    {{< rightStep size="5" >}}

<p>For this workshop, we'll be working out of the Developer Console.</p>
<ol>
  <li>In the upper-left corner of the screen, underneath the Red Hat OpenShift logo, click on the <strong>Administrator</strong> dropdown to switch to the <strong>Developer</strong> console.</li>
</ol>
    {{< /rightStep >}}
{{< /twoSideStep >}}