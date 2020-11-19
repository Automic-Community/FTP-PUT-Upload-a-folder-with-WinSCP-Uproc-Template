*FTP PUT Upload a folder with WinSCP Uproc Template*
=============


This is a template to transfer a folder and all the files and folders containes to a remote server using FTP/SFTP/SCP.
http://github.com/Automic-Community/FTP-PUT-Upload-a-folder-with-WinSCP-Uproc-Template

<!-- List of attached files -->
Contents of Solution Package:

						
								*TEMPLATE_FTP_TRANSFER_WITH_WINSCP.zip
								
								*119-image1.jpg
								
						


Documenation and Instructions
---

<p><span><strong class="bbc">Description</strong></span><br /><br />This is a template to transfer a folder and all the files and folders containes to a remote server using FTP/SFTP/SCP.<br />This Uproc uses WinSCP to perform the transfer.<br /><br />Compatibility:</p>
<p><br /><br /></p>
<ul class="bbc">
<ul class="bbc">
<li>This Uproc is compatible with Dollar Universe 6.</li>
</ul>
</ul>
<p>&nbsp;</p>
<ul class="bbc">
<ul class="bbc">
<li>The transfer has to be done from a Windows</li>
</ul>
</ul>
<p>&nbsp;</p>
<ul class="bbc">
<ul class="bbc">
<li>The transfer can be done to any FTP/SFTP/SCP server</li>
</ul>
</ul>
<p><br /><br /></p>
<p><span><strong class="bbc">Implementation</strong></span><br /><br />This short video shows the basic configuration steps:<br /><br />http://vimeo.com/82368717<br /><br /><br />The step by step procedure:</p>
<p><br /><br /></p>
<ul class="bbc">
<ul class="bbc">
<li>Import the package file (.unipkg) in the list of package with UniViewer</li>
</ul>
</ul>
<p>&nbsp;</p>
<ul class="bbc">
<ul class="bbc">
<li>Deploy the package to the Dollar Universe</li>
</ul>
</ul>
<p>&nbsp;</p>
<ul class="bbc">
<ul class="bbc">
<li>Duplicate the Uproc to have the uproc with the desired name</li>
</ul>
</ul>
<p>&nbsp;</p>
<ul class="bbc">
<ul class="bbc">
<li>Update the uproc<br /><br /><br />
<ul class="bbc">
<ul class="bbc">
<li>In the associated file</li>
</ul>
</ul>
<br />
<ul class="bbc">
<ul class="bbc">
<li>Open WinSCP.ini with a text editor</li>
</ul>
</ul>
<br />
<ul class="bbc">
<ul class="bbc">
<li>Close WinSCP.ini file without changing anything</li>
</ul>
</ul>
<br />
<ul class="bbc">
<ul class="bbc">
<li>Open WinSCP.exe with the default system file association</li>
</ul>
</ul>
<br />
<ul class="bbc">
<ul class="bbc">
<li>Configure the target server, test the connection and save this configuration in a "Stored Session" (save also the password)</li>
</ul>
</ul>
<br />
<ul class="bbc">
<ul class="bbc">
<li>Close WinSCP.exe</li>
</ul>
</ul>
<br /><br /></li>
</ul>
</ul>
<p>&nbsp;</p>
<ul class="bbc">
<ul class="bbc">
<li>In the Uproc Variables: Update the Uproc with the required detail (including the name of the "Stored Session")</li>
</ul>
</ul>
<p><br /><br /></p>
<p><span><strong class="bbc">Note</strong></span><br /><br />WinSCP is called from the Uproc Internal Script. This Template can then easily be customized.</p>

Copyright and License
---

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)


Questions or Need Help? 
---
Join the [Automic Community Integrations](https://community.broadcom.com/communities/community-home?CommunityKey=83e49dd4-b93e-464a-a343-2bb1e51c13ec) to discuss this integration.
