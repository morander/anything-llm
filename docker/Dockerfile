# Brand3y: Add MCP configuration
USER root
RUN mkdir -p /app/server/storage/plugins
COPY server/storage/plugins/anythingllm_mcp_servers.json /app/server/storage/plugins/anythingllm_mcp_servers.json
RUN chown -R anythingllm:anythingllm /app/server/storage && \
    chmod 644 /app/server/storage/plugins/anythingllm_mcp_servers.json
USER anythingllm
