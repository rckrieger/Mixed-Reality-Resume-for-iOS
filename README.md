# Mixed-Reality-Resume-for-iOS
In order to learn more about mixed reality for iOS, I built out my resume using reality composer. 

Here are here key findings
- Text background options would improve readability
- Adding gifs/ videos is unintuitive 
- Developer would benifit from a return to anchor keyboard shortcut
- Needs spellcheck intergration
- Cool feature would be making images respond to focus (might be possible programmatically but not in Reality Composer)
- If you add the wrong picture to Reality composer and then delete it, it sticks in the metadata and is nearly impossible to 
remove from the project. If this fails to compile, its because the only way I found to "remove" the wrong pictures is not to git commit
them.

Demo


https://user-images.githubusercontent.com/10582919/181585548-3d5a58d4-a6e5-4c74-8c59-ede5f4f417e9.mov



Want to build your own project like this? Here's the steps I (should have) took:
</br>
1. When creating a new project in Xcode, hit augmented reality app. Pick UiKit/Storyboard, NOT SwiftUi. With Xcode 12 the SwiftUI augmented reality starter project will not build and you'll get error messages. You don't need that negativity in your life. Pick UI kit.
<img width="667" alt="Screen Shot 2022-07-28 at 12 37 53 AM" src="https://user-images.githubusercontent.com/10582919/181448745-0cef6158-91a8-4f49-a8ee-b7b774afee11.png">
</br>
2. Select Experience. Click open in Reality composer.<img width="777" alt="Screen Shot 2022-07-28 at 12 43 23 AM" src="https://user-images.githubusercontent.com/10582919/181449899-f176d103-f228-4f05-9552-2a7d67ddc235.png">

3. Drag and drop photos from iPhoto. Videos and gifs dropped from iPhoto do not work and will be inserted as stills.
4. Build.
