https://juejin.cn/post/7235539402868277285
掘金老哥写的hello插件
使用chatgpt 提问hello 会返回 hello 的功能
使用了
https://ngrok.com/
这个要花钱的,没花钱会展示一个警告画面妨碍访问
(replit上在线创建(付费版 api自身可以使用,但是导入chatgpt时候报错 原因不明))

内网穿透使用方法:
```ngrok http 3000```




# Express ChatGPT Plugin Starter 🚀

The Express ChatGPT Plugin Starter is a foundational project for creating a ChatGPT plugin with Express.js. It serves as a boilerplate for developers to build and deploy plugins for ChatGPT.

## Project Structure 📁

- `server.js`: The main Express.js server file, sets up a basic server and a '/hello' endpoint.
- `package.json`: Specifies the project dependencies and scripts.
- `public`: Contains public assets served by the Express.js server, including `openapi.yaml` (an OpenAPI specification for the '/hello' endpoint) and `ai-plugin.json` (the plugin configuration file).

## Getting Started 🏁

1. Clone the repository.
2. Navigate to the project directory.
3. Install the dependencies by running `npm install`.
4. Start the server by running `npm start`.

## Customization 💡

To customize this starter project for your own ChatGPT plugin:

- `server.js`: Add your own endpoints.
- `openapi.yaml`: Update the OpenAPI specification to match your new endpoints.
- `ai-plugin.json`: Update the plugin details.

## Contributing 🤝

Contributions are welcome! Feel free to open an issue or submit a pull request for improvements or additions to this project.
