## YouTube embed example

The YouTube URL of the video is https://www.youtube.com/watch?v=JLMbpiywVxQ. 

Here is how to embed a clickable preview:

```markdown
[![Final video of fixing issues in your code in VS Code]
(https://img.youtube.com/vi/JLMbpiywVxQ/maxresdefault.jpg)]
(https://www.youtube.com/watch?v=JLMbpiywVxQ)
```

Which shows as:

[![Final video of fixing issues in your code in VS Code](https://img.youtube.com/vi/JLMbpiywVxQ/maxresdefault.jpg)](https://www.youtube.com/watch?v=JLMbpiywVxQ)

Here is how to embed the video:

{% raw %}
{% include youtube.html id="JLMbpiywVxQ" %}  
{% endraw %}

{% include youtube.html id="JLMbpiywVxQ" %}  

To enable this, you need to create an `_includes` folder in your GitHub Pages root folder and include the [youtube.html](youtube.html) file from this repository.