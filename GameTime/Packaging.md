# Tiled level in Gametime - Packaging

### Issue
After you package your project, despite the packaging process succeed, all the functionality from your system may just fail. This also occurred when you use **Standalone Game** instead of **Selected Viewport** to play in editor.

### Solution
Somehow, you need to let your **game instance** know that your **Tiled Level Gametime System** (a game instance subsystem) exists, otherwise, the packaged project will not include that system. Just let your game instance know there exists a system when init. Create a game instance class and set it in your project setting. Override **Init**, add anything that may take reference from your **Build System**, such as print its name. Then, it should just work accurately.

**Instruction Video:**
[![Cover](../_media/GametimeQuickStart/VideoCover.png)](https://youtu.be/WDopi9N5LBw)