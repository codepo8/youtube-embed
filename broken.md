# How not to embed YouTube videos in GitHub pages

If the YouTube URL of the video is https://www.youtube.com/watch?v=JLMbpiywVxQ you can just paste the HTML into markdown but for sensible repositories, it will break builds as it is invalid markdown.

<iframe width="560" height="315" src="https://www.youtube.com/embed/JLMbpiywVxQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Instead use a [clickable preview](demo-preview.md) or an [include](demo.md).