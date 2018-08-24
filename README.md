# Cấu trúc của một project react-native
Các ví dụ em có nêu cụ thể ^^.

```
Root
├── app
│   ├── api
│   │   ├── AuthApi.js // những cái này nên đặt rõ ràng, để sau này import cho dễ
│   ├── components
|   |	├── elements
|   |	|    ├── Input.js
|   |	|    ├── Button.js
|   |	|    ├── .....
|   |	├── layout
|   |	|    ├── Screen.js
|   |	|    ├── Navbar  // ví dụ Navbar này cấu trúc theo kiểu folder, trong trường hợp Navbar có các trường con
|   |	|    |     ├── index.js
|   |	|    |     ├── IconRight.js 
│   ├── containers
|   |	├── LoginContainer // Thường đặt theo cấu trúc này, bởi trong các màn hình có thể có các phần phụ, nên để dự phòng.
|   |	|    ├── index.js
|   |	|    ├── utils.js
|   |	├── HomeContainer
|   |	|    ├── index.js
|   |	|    ├── utils.js
|   ├── redux
|   |	├── actions
|   |	├── reducers
|   |	|   ├── auth.js
|   |	|   ├── index.js
|   |   ├── configureStore.js
|   |	├── Root.js
│   ├── navigation // Chứa các file config Navigation
│   ├── theme // Chứa các file cấu hình
|   |   ├── color.js
|   |   ├── font.js
|   |   ├── image.js // File này chứa các import image
│   ├── images // chứa các file ảnh
│   |   ├── abc.png
│   ├── utils // chứa các function helpers
│   |   ├── abc.png
│   ├── App.js

```
