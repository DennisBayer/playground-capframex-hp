# Welcome to CapFrameX

*CapFrameX* is frametimes capture and analysis tool compatible with most common 3D APIs. It offers a rich feature set to record and analyze GPU and CPU benchmarks.

It enables you to analyze and compare records in multiple ways. The FPS-, Frametime-graphes and L-Shapes are calculated for each record and can be compared among each others. The calculation considers various options, e.g. Shuttering Parameter and Adaptive Scattering Measure.

Although based on PresentMon, which covers all 3D APIs, OCAT records can be imported as well.

## Current feature list

### Capture frametimes

* Capture service based on PresentMon
* High-accurate frametime recordings
* Predefined capture time
* Managing processes to capture
* DirectX and Vulkan are supported
* Free configurable hotkeys
* Very reliable hotkey hooking

### Single record analysis

* Select and search recordings in DataGrid
* Displaying system info like CPU and GPU
* Editing comments and system info
* Direct editing comments and system info in record list
* Displaying frametime graph and moving average
* Displaying FPS graph and average line graph
* Cutting frametime graphs ("Single Record" page)
* Calculating and displaying basic parameter (average, p-quantiles, min)
* Calculating and displaying low average parameter (0.1% and 1% low)
* Calculating and displaying adaptive standard deviation
* Calculating and displaying stuttering percentage (time)
* Removing outliers

### Record comparison

* Record comparison (performance parameter, L-shape analysis)

### L-shape analysis

* Calculating and displaying L-shape curve

### Synchronization info (G-Sync, FreeSync)

* Displaying frametime and display changed time graph (G-Sync and FreeSync synced vs. dropped frames)

### Reporting

* Export performance parameter and graphs (Excel)
* Export comparison table as report (Excel)
* Export PNG report picture

## Recent Announcement

<ul>
  {% for post in site.posts limit: 3 %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> - <small><time>{{ post.date | date: "%b %-d, %Y" }}</time></small>
    </li>
  {% endfor %}
</ul>
<small><a href="{{ site.baseurl }}{% link pages/announcements.html %}">Read more</a><small>

## Screenshots

![Single Record View](./assets/images/SingleRecordView.png "Single Record View")

## Disclaimer

*CapFrameX* is currently under development and in a beta stage. Bugs might occur - feel free to open an issue or provide a pull request.

## Support and Contact

* ComputerBase.de: [CapFrameX - Capture und Analyse Tool - German user and development forum thread](https://www.computerbase.de/forum/threads/capframex-capture-und-analyse-tool.1851025)
* Twitter: <https://twitter.com/CapFrameX>
* YouTube: [CapFrameX Capture Page Tutorial - Frametimes aufzeichnen [DE]](https://youtu.be/ZqMMPDxJUkk)
