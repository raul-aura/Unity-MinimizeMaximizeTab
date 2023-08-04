# Unity Minimaze/Maximize Tab
The Minimize/Maximize Tab script allows you to create a toggleable behavior for GUI objects that use the Canvas Group component. This script enables you to create collapsible panels, images, or any other GUI element that you want to hide or show with a smooth animation.

![Screenshot](unitytabpreview.gif)

## 🛠️ HOW TO INSTALL

- Install and import the [`MinimizeMaximizeTab.unitypackage`](MinimizeMaximizeTab.unitypackage).
- Move the "MinimizeTab.cs" script inside your Unity project.
- Adjust to your liking and you're done!

## 🗔 HOW TO USE

1. **Add a Canvas Group**: Attach a Canvas Group component to the objects that you want to group and make collapsible. The Canvas Group component controls the visibility and interaction of the object.
2. **Create an Empty Object**: Create an empty GameObject in your Unity scene. This empty GameObject will act as the controller for the grouped objects and can be an empty parent.
3. **Add MinimizeTab Script**: Attach the MinimizeTab script to the empty GameObject you created in the previous step.
4. **Reference Needed Objects**: In the Inspector window, you will find two fields named "Max Tab" and "Min Tab" in the MinimizeTab script component. Drag and drop the GameObjects that you want to group and toggle between these fields. The "Max Divider" represents the object shown when the group is expanded, while the "Min Divider" represents the object shown when the group is collapsed.
5. **Toggle the Tabs**: You can now call the "ToggleTabs" function from the MinimizeTab script to toggle the visibility of the grouped objects. You can trigger this function using a button or another script.

## 🫶 CONTRIBUTION
If you find any issues or have suggestions for improvements, please feel free to create an issue or a pull request. Your contributions are more than welcome! :)

<hr>
<p align="center">
Yours Truly, Aura.
</p>
