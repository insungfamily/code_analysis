string selectedFilePath = [[ShowOpenFileDialog]]();
if (selectedFilePath != null)
{
    [[LoadImage]](selectedFilePath);
}