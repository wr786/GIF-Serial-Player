# GIF Serial Player
> A local UI for playing a sequence of images

## Usage

- Copy your image serial into `./images/`

- Rename them, like `1.jpg`, `2.jpg`，..., `37510.jpg`.

- Edit `./index.html`

  ​	You can find:

  ```javascript
  // ==================可编辑区=================
  var folderName = "images";      // 图像位于的文件夹位置，默认为images   
  var tot = 1;                  // 图像总数
  var speed = 200;                // 每几微秒播放下一帧，数值越大播放越慢
  var fileType = ".jpg";          // 图片后缀名
  // ==================可编辑区=================
  ```

  - Edit `folderName` if you put image serial into another folder (not `./images/`)
  - Edit `tot` to the number of your images, like `37510`
  - Edit `speed` to adjust play speed, the **higher** the `speed` is, the **slower** the player plays.
  - Edit `fileType` if your images are `.png` or whatever.

- Open `./index.html` in your web browser and try the buttons! Now you can play your image serial!