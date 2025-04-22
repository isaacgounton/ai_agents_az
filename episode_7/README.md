# Episode 7: Creating Youtube short videos using our custom MCP server

## Get the template

- [Template: Create youtube shorts using MCP + n8n](youtube_shorts_with_mcp_server.json)

## MCP server

### How to run it

```bash
LOG_LEVEL=debug PEXELS_API_KEY= npx short-video-creator
```

Alternatively

```bash
docker run -it --rm --name shorts-creator -p 3123:3123 -e PEXELS_API_KEY=-e LOG_LEVEL=trace short-video-creator-short-creator
```

### Resources

- [Github](https://github.com/gyoridavid/short-video-maker)
- [npm](https://www.npmjs.com/package/short-video-maker)
- [Docker](https://hub.docker.com/r/gyoridavid/short-video-maker)

## Watch the video

[![Automated faceless video generation (n8n + MCP) with captions, background music local and 100% free](https://img.youtube.com/vi/jzsQpn-AciM/0.jpg)](https://www.youtube.com/watch?v=jzsQpn-AciM)
