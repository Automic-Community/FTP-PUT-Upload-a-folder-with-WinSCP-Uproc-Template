*FTP PUT Upload a folder with WinSCP Uproc Template*
=============


This is a template to transfer a folder and all the files and folders containes to a remote server using FTP/SFTP/SCP.
http://github.com/Automic-Community/FTP-PUT-Upload-a-folder-with-WinSCP-Uproc-Template

<!-- List of attached files -->
Contents of Solution Package:

						
								*Dollar_Universe-template_ftp_folder_transfer_with_winscp.zip
								
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

Solutions, Templates, Actions and other content available on the Automic Marketplace subject to the Automic [Developers Distribution License] (https://marketplace.automic.com/developers-distribution-license) as well as the Automic Community [Terms of Service] (https://marketplace.automic.com/community-terms-of-service).
Automic does not support, maintain or warrant any content submitted by the Automic Community.



Questions or Need Help? 
---
Any questions or comments? Converse with your fellow Users in the [Automic Community] (https://community.automic.com).