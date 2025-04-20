<%*
const folder = "ttrpgs - Copy/Aravoth";  // Path to your folder
const notes = app.vault.getFiles().filter(f => f.path.startsWith(folder) && f.extension === 'md');

for (const note of notes) {
    const file = await app.vault.read(note);
    const modified = tp.file.frontmatter.modified;  // Get the modified date from the frontmatter
    
    // Prepare the footer
    const footer = `\n\n---\nThis page was last edited on \`= ${modified}\`.`;

    // Add the footer to the content
    const updatedContent = `${file}${footer}`;

    // Write the updated content back to the file
    await app.vault.modify(note, updatedContent);
}
%>
