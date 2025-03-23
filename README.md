### ⚡️ 项目1：多线程分段下载器

**核心目标**：用多线程加速文件下载，练习线程协作和资源管理。  
**技术要点**：

- 使用 `HttpURLConnection` 获取文件总大小，计算每个线程下载的字节范围。
    
- 创建多个线程分别下载不同片段（`Range: bytes=0-1000`）。
    
- 用 `CountDownLatch` 或 `CompletableFuture` 等待所有线程完成。
    
- 合并临时文件，处理中断恢复（可选）。  
    **关键知识点**：

\`\`\`python
print(“Hello, World!”)
\`\`\`
