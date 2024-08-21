# ImageJ update site

<warning>
While we provide JIPipe via the ImageJ update site system, we highly recommend to use a <i>prepackaged</i> version of our software.
The reason behind this is that JIPipe requires a variety of ImageJ plugins to work properly. 
Those are by default not provided by the Fiji distribution of ImageJ and may yield in a non-functional JIPipe installation.
</warning>
<warning>Please do <strong>not</strong> combine the ImageJ Update Site package with the <a href="Manual-installation.md">manually installed JAR files</a>. 
The files may conflict and will cause errors.</warning>

<procedure title="Installing JIPipe as plugin">
<step>
Download a version of <a href="https://fiji.sc/">Fiji</a> for your operating system. Extract the package with the tools provided by your operating system.
</step>
<step>
Start Fiji and go start the update manager by navigating to <ui-path>Help | Update...</ui-path>. Follow the instructions until the update manager is ready. You should be able to see a button <control>Manage Update Sites</control>.
<note>You might be prompted to restart ImageJ. Restart ImageJ and re-launch the updater.</note>
</step>
<step>
Please select the following update sites from the list:
<ul>
<li><code>3D ImageJ Suite</code></li>
<li><code>clij</code></li>
<li><code>clij2</code></li>
<li><code>IJ-OpenCV-Plugins</code></li>
<li><code>IJPB-Plugins</code></li>
<li><code>ImageScience</code></li>
<li><code>Multi-Template-Matching</code></li>
<li><code>OMERO 5.5-5.6</code></li>
<li><code>JIPipe</code></li>
</ul>
</step>
<step>
Click <control>Apply and Close</control> and then <control>Apply Changes</control>.
</step>
<step>
Restart ImageJ as instructed.
</step>
<step>To start JIPipe navigate to <ui-path>Plugins | JIPipe | JIPipe GUI</ui-path></step>
</procedure>

<seealso>
<category ref="related">
<a href="User-interface.md">User interface overview</a>
</category>
</seealso>