# Manual installation

<note>We provide JAR files that can be manually installed into an existing ImageJ instance. This is different from using the ImageJ Updater.</note>
<warning>We highly recommend to only use our prepackaged JIPipe versions if possible, as JIPipe requires a variety of ImageJ plugins to work propertly. 
Those are not provided with the JAR package.</warning>
<warning>Please do <strong>not</strong> enable the JIPipe update site while using a manually installed plugin. 
The files may conflict and will cause errors.</warning>

<procedure title="Manual JIPipe installation">
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
</ul>
<warning>Do <strong>not</strong> select the <code>JIPipe</code> update site!</warning>
</step>
<step>
Click <control>Apply and Close</control> and then <control>Apply Changes</control>.
</step>
<step>
Restart ImageJ as instructed.
</step>
<step>
If applicable, download the <a href="https://jipipe.hki-jena.de/download">JAR package (custom installation)</a> package from the JIPipe website.
</step>
<step>
Extract the package and copy its contents into the <path>Fiji.app/plugins/JIPipe</path> directory (create the directory if needed).
<tip>macOS: Right-click the app and select <control>Show Package Contents</control> to display the plugins directory in Finder.</tip>
</step>
<step>Restart Fiji</step>
<step>To start JIPipe navigate to <ui-path>Plugins | JIPipe | JIPipe GUI</ui-path></step>
</procedure>

<seealso>
<category ref="related">
<a href="User-interface.md">User interface overview</a>
</category>
</seealso>