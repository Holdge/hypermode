# Arcome Privacy Policy / 隐私政策

Updated: 2026-11-12. Publisher: Holdge. Contact: holdgewong@gmail.com.

## Local data / 本机数据
Arcome stores workspaces, folders, favorites, conversation history, selected attachments and optional screenshot previews in your browser extension storage. It does not use browser account sync storage. The publisher operates no analytics or conversation collection server and does not sell user data.

## AI services / AI 服务
You choose and configure an AI service. When you submit a question, your question, relevant conversation messages and the context or attachments you selected are sent to that service. Images are compressed; text, PDF and Word documents are parsed locally. Connection validation sends your API key to the selected service with a model-list request. External AI website handoff fills your question and selected text context into the website. Automatic sending can be disabled. Each provider handles requests under its own privacy policy. The extension does not include a publisher-provided AI account or API key.

## Credentials / 密钥
API keys remain in the current browser session by default. If you explicitly enable remembering a key, the extension stores it locally. This storage is not a separate encrypted credential vault. A key saved for one API endpoint is not automatically reused at another endpoint.

## Browser access / 浏览器权限
Tab titles, URLs and loading state are used to display, search and manage browser instances. Optional history access enables local browser-history browsing and search after permission is granted. The homepage can display visited web pages by date and reopen them. Loaded history results remain in the current page memory and are not copied to a separate persistent history database or automatically sent to an AI service. Optional page preview access captures only visible ordinary web pages already in the workspace; it excludes incognito and browser-internal pages. Screenshot previews are local and capped at 80 images, seven days and approximately 5 MB. Disabling previews clears the screenshot cache. Optional website access is used for the selected AI endpoint and page previews. External AI scripts operate on supported AI websites for input handoff.

首页访问历史需要单独授权。可按日期查看、搜索和重新打开此浏览器访问过的网页，不限 Space。已加载结果仅保留在当前页面内存中，不额外创建历史数据库，也不会自动发送给 AI。Chrome 删除历史或撤销权限后，列表会清除或更新。

## Optional Web Workbench / 可选网页工作台

The optional Web Workbench requests scripting access and access to the site you choose. When you send a question or run a webpage task, the text, title, and links needed for that request, plus relevant conversation context, are sent to the AI service you configured. Generating an appearance preview may send the page title and labels for candidate areas to that service. The workbench does not read passwords or existing input values. It asks for confirmation before opening a link, clicking a page control, or filling a field. It stores the current-page conversation in browser session storage and saved appearance rules on the device. Saved rules are applied locally when you revisit an authorized site. You can revoke access in Chrome's extension settings.

网页工作台是可选功能。启用时会申请脚本权限和你选择的站点权限。发送网页提问或运行网页任务时，所需的页面正文、标题、链接和相关对话会发送给你配置的 AI 服务。生成外观预览时，可能会发送页面标题和可调整区域的标签。工作台不读取密码或输入框里已有的值，打开链接、点击控件或填入文字前会请你确认。当前页的对话保存在浏览器会话中，保存的外观规则留在本机，并在你再次访问已授权站点时本地应用。你可以在 Chrome 扩展设置中撤销授权。

## Homepage calendar / 首页万年历
The optional homepage calendar requests historical events from Chinese Wikipedia using the selected month and day. Like other network requests, it may expose your IP address to that service. It does not include workspace content, conversations or credentials. Holiday references open only when you follow a source link. The programmer almanac is generated locally for the selected date. You can hide the calendar in appearance settings.

首页万年历可在外观设置中关闭。历史事件请求只包含所选月、日，网络连接可能向中文维基百科披露设备 IP 地址，不附带工作区、对话或密钥。放假说明带有来源链接，程序员黄历按所选日期在本机生成。

## Optional local tools / 可选本机工具
An optional local companion manages workspaces through CLI / MCP and imports Arc workspace directory metadata on macOS. It does not import passwords or cookies. Its authenticated communication is restricted to the local machine.

## Control and deletion / 控制与删除
You can remove your API key through AI settings, disable optional features and revoke browser permissions. Conversations can be moved to trash; this version does not provide a permanent-empty-trash control. Uninstalling the extension normally removes its browser extension storage. Export data you need before uninstalling. Exported backups and optional companion files remain under your control and must be deleted separately. Data already sent to an AI provider is subject to that provider's retention and deletion process.

## Limited use / 使用限制
The use and transfer of information received from Google APIs will adhere to the Chrome Web Store User Data Policy, including the Limited Use requirements. Data is used only to provide user-facing workspace, search and AI features. It is not used for advertising, sold to data brokers, or used by the publisher to train generalized AI models.

## Contact / 联系
For privacy questions, contact holdgewong@gmail.com. Do not include API keys, passwords, private conversations or confidential files in a public support issue.

## Web search / 网页搜索

General web searches use Chrome Search API and the default provider selected in Chrome. Query text is sent to that provider under its privacy policy. Arcome does not read, modify or replace the default search setting and does not operate a query-collection server. Saved search queries stay in local extension storage. Explicit site-scoped searches go to the selected website. 普通网页搜索遵循 Chrome 默认搜索服务；搜索记录保存在本机。
