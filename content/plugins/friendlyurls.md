Tags: plugin
Bundle: free

# FriendlyUrls plugin

Renamed to [FolderResizeSyntax](/plugins/folderresizesyntax) and merged into the Core, ImageResizer.dll in 3.0.12. This change reduces the number of dlls you need to deploy, and simplifies migration for v2 customers.

You should change `<add name="FriendlyUrls" />` to `<add name="FolderResizeSyntax" />` in Web.config and remove ImageResizer.Plugins.FriendlyUrls.dll  through Project References, /bin/, or nuget.