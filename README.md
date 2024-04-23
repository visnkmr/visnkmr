![](https://komarev.com/ghpvc/?username=visnkmr)
      
[![](https://img.shields.io/badge/-Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/vishnunk-59124/)
[![](https://img.shields.io/badge/-Telegram-white?style=flat-square&logo=telegram)](https://vishnunkmr.t.me/)
[![](https://img.shields.io/badge/-Codeberg-white?style=flat-square&logo=codeberg)](https://codeberg.org/visnk)
[![](https://img.shields.io/badge/-Youtube-red?style=flat-square&logo=youtube)](https://youtube.com/@vishnunk)
[![](https://img.shields.io/badge/-Gmail-white?&style=flat-square&logo=Gmail)](mailto:visnkmr@gmail.com)

[![](https://data.jsdelivr.com/v1/package/gh/vishnunkmr/quickupdates/badge)](https://www.jsdelivr.com/package/gh/vishnunkmr/quickupdates)

<!-- <br>

![](https://cdn.jsdelivr.net/gh/visnkmr/visnkmr.github.io@main/appstore/images/bapl.png) 
![](https://cdn.jsdelivr.net/gh/visnkmr/visnkmr.github.io@main/appstore/images/pm.png) 
![](https://cdn.jsdelivr.net/gh/visnkmr/visnkmr.github.io@main/appstore/images/nokb.png)  
-->
      
# Open Source Repos    

|  <a href="https://github.com/visnkmr/filegpt-filedime">![fgpt] </a>  | <a href="https://github.com/visnkmr/filedime">![filedime] </a>|
| :------------: | :--------: |
| <a href="https://github.com/visnkmr/LogLink2Disk_chrome">![lldchrome] </a>   | <a href="https://github.com/visnkmr/prefstore">![prefstore] </a>|
| <a href="https://github.com/visnkmr/netspeed_pc">![nspc] </a>   | <a href="https://github.com/visnkmr/onscreenkeyboard">![osk] </a>|
| <a href="https://github.com/visnkmr/wfmossfrontend">![wfmossfrontend] </a>  | <a href="https://github.com/visnkmr/perlink">![perlink] </a> |

![graph]  

### 📊 Github Stats
<a href='https://github.com/visnkmr/visnkmr'>  

![Stats Overview](https://cdn.jsdelivr.net/gh/visnkmr/github-stats-transparent@output/generated/overview.svg)
![Most Used Languages](https://cdn.jsdelivr.net/gh/visnkmr/github-stats-transparent@output/generated/languages.svg)

</a>
<br>


  - [FileGPT-Filedime](https://github.com/visnkmr/filegpt-filedime) an api provider backend in python for quering files in [filedime](https://github.com/visnkmr/filedime] using llama3 and meloTTS, a more natural TTS model in Filedimespeech or via chrome extension for use in browsers. Uses RAG retrieval for fetching relevant content when quering.
  - [Wireless File Manager OSS Frontend](https://github.com/visnkmr/wfmossfrontend) using the REST API provided by [Wireless File Manager](https://github.com/visnkmr/wfm) app.
  - File Explorer with built in markdown viewer for Windows, Mac, Linux (Work In Progress)
      - [Single App](https://github.com/visnkmr/filedime). ~1MiB (Rust and Tauri)
      - [Markdown Viewer only](https://github.com/visnkmr/markdown_viewer_pc/). <1MiB (Rust and Tauri)
  - Netspeed monitor for Windows, Mac, Linux
      - [Single App](https://github.com/visnkmr/netspeed_pc/releases/latest). (Size:1MiB) (Tauri: HTML, CSS, JS (Typesript) GUI and Rust backend)
        - [Single app Using SSE](https://github.com/visnkmr/netspeed_pc) (recommended)
        - [Single App Using Tauri's inbuilt websocket](https://github.com/visnkmr/netspeed_tauri_websocket)
      - Backend and GUI separate
          - Server (Rust) ~300KiB
            - [Netspeed SSE Server Single Client](https://github.com/visnkmr/netspeed_server/releases/latest)
            - [Netspeed SSE Server Multi client](https://github.com/visnkmr/netspeed_server/tree/multi_sse_atomic)
            - [Netspeed HTTP Server](https://github.com/visnkmr/netspeed_server_http/releases/latest)  
          - GUI for Netspeed SSE Server
            - [Netspeed GUI - 950KiB (Tauri)](https://github.com/visnkmr/netspeed_gui/releases/latest)
            - [Netspeed GUI -11 MiB (Python)](https://github.com/visnkmr/ns_gui/releases/latest)  
          - Single Control UI (TCL)
            - [Control Center](https://github.com/visnkmr/netspeed_monitor_control_center)
  - SSTP: Save sessions tabs to MySQL. It is a project that lets user save tabs to a MySQL db through a vercel api endpoint. It functions similar to onetab only difference being it lets users save the tabs to a MySQL db. It is completely self hostable using your own instance of mysql db instead of MySQL and local rust server instead of using vercel endpoint.
  - Rust crates
    - [Prefstore](https://github.com/visnkmr/prefstore) 
    - [Xbel-parser (NPAY)](#)
    - [Json-bookmark-parser (NPAY)](#)
  - LogLinktoDisk (Javascript & Chrome,Firefox APIs) : to save Link/links to markdown file locally like Onetab extension but with local disk storage.
    - Extensions (JS, HTML)
      - [Chrome extension](https://github.com/visnkmr/LogLink2Disk_chrome)
      - [Firefox extension](https://github.com/visnkmr/LogLink2Disk_Firefox_extension)
    - LLD SavetoDisk: Backend for LogLinktoDisk (Rust)
      - [SavetoDisk](https://github.com/visnkmr/savetodisk)
    - LLD ServeLocal: Backend for LogLinktoDisk (Rust) that along with saving locally + also serves the last saved session over lan network
      - [SavetoDisk](https://github.com/visnkmr/savetodisk/tree/serve_markdowns)
    - LLD Perlink: Backend for LogLinktoDisk (Rust) that does not save to disk but shows options to choose browser to open link in.
      - [SavetoDisk](https://github.com/visnkmr/savetodisk/tree/open_link_in)
  - Perlink let you Choose browser to open on per link basis on windows, linux and mac. (Rust)
    - [Perlink](https://github.com/visnkmr/perlink)   
  - Weblinklist(NPAY)
    - [NodeJS](#)
    - [Rust](#)
  - [On Screen Remote](https://github.com/visnkmr/onscreenkeyboard) app for PCs like the remote offered by NoKeyboard on Android.
  - Take Notes (Kotlin): Uses coroutine, datastore
  - ADB Keyboard, Remote and Shell (Java)


# Android apps, Desktop Apps, Libs

<b><i>Powering 15million+ sessions.</i></b>

  <div>
    <a href="https://play.google.com/store/apps/developer?id=Vishnu+N+K"><img width="130px" src="https://play.google.com/intl/en_us/badges/images/badge_new.png" class="storebs bmargins" /></a>
              <a  href="https://www.amazon.com/gp/mas/dl/android?p=io.github.visnkmr.bapl&showAll=1"><img width="130px" src="https://images-na.ssl-images-amazon.com/images/G/01/mobile-apps/devportal2/res/images/amazon-appstore-badge-english-white.png" class="storebs bmargins" /></a>
<!--                   <a  href="https://apps.microsoft.com/store/search?publisher=Vishnu%20N%20K"><img width="130px" src="https://get.microsoft.com/images/en-us%20dark.svg" class="storebs bmargins" /></a> -->
  </div>

| <a href="https://github.com/visnkmr/backgroundappslist">![bapl] </a>   | <a href="https://github.com/visnkmr/wfm">![wfm] </a>|
| :------------: | :--------: |
| <a href="https://github.com/visnkmr/timenetspeed">![tns] </a>   | <a href="https://github.com/visnkmr/netspeed-test">![nst] </a>|
| <a href="https://github.com/visnkmr/takenotes">![tn] </a>   | <a href="https://github.com/visnkmr/powermenu">![pm] </a>|
| <a href="https://github.com/visnkmr/file_explorer">![fx] </a>   | <a href="https://github.com/visnkmr/nokeyboard">![nk] </a>|

- Background Apps and Process List (Java) : Uses API, Volley, Accessibility in unreleased Autoclose version of the app.
- File Explorer (Java) : Uses ForkJoin pool, Fuzzy Logic based search, Memoization, Glide, GSON, Recycleview.
- Wireless File Manager (Java & WebUI frontend using NextJS, React, Tailwind)
- No Keyboard (Java)
- Netspeed Test (Java)
- Taotlus (Java,Kotlin) : Use coroutine, picasso, fuzzy logic based search, recycleview.
- Teave (Java)
- Time Netspeed Monitor (Java) : Uses Overlay.
- Calculator (Java)
- Software Power Menu (Java)
- Software Volume Button (Java)
- Developer Tools Menu for Fire TV (Java)

Github CI/CD pipelines to remember:
- Appcenter->MySQL (visnkmr/apihub) [rust program run as daily cron job using ghAction]
- Codeberg->JSON (visnkmr/apihub@getnewcommits) [rust program run as daily cron job using ghAction]
- visnkmr/homepagev2 NextJS page built and push the exported files to visnkmr/visnkmr.github.io and codeberg pages repo which is then served over jsdelivr cdn for website visnkmr.github.io and visnk.codeberg.page [whenever new code pushed to main runs ghAction]
- visnkmr/edge_release publishes a release whenever new version of edge available for linux. [rust program run as daily cron job using ghAction]
- visnkmr/filedime,visnkmr/wfmossfrontend auto release github action including artifacts for apple silicon devices.
   
🛠️ Rust, Typescript, Java (Android), Kotlin  (Android), Javascript, HTML, CSS, Python, R, Swift (Basics), TCL, Linux, bash scripting  
🖥️ Arch GNU/Linux, Win11  
Local(SH): Gitea, Floccus, Dufs, Olivetin, Joplin, Weblinklist,Proxmox*, Nextcloud*, Github workflow.  
Helpful scripts: 
  - [ChecknLock](https://github.com/visnkmr/checknlock)
  - [Codeberg,Gitea->JSON File, Appcenter->MySQL](https://github.com/visnkmr/apihub)
  - [Linux Disk Usage Monitor (Rust)](https://github.com/visnkmr/dude)
  - SMS WordCloud (R)
  - CSV Data Analyzer (R)
    - Amazon Appstore Sales 
    - Google Play Console

  
![](https://cdn.jsdelivr.net/gh/visnkmr/visnkmr.github.io@main/images/amzstore.webp)  
<br>  
![](https://cdn.jsdelivr.net/gh/visnkmr/visnkmr.github.io@main/images/gplay.webp)  
<!--
**visnkmr/visnkmr** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<!----------------------------------{ reference links }--------------------------------->

[filedime]: https://github-readme-stats.vercel.app/api/pin/?username=visnkmr&repo=filedime
[wfmossfrontend]: https://github-readme-stats.vercel.app/api/pin/?username=visnkmr&repo=wfmossfrontend
[lldchrome]: https://github-readme-stats.vercel.app/api/pin/?username=visnkmr&repo=LogLink2Disk_chrome
[prefstore]: https://github-readme-stats.vercel.app/api/pin/?username=visnkmr&repo=prefstore
[perlink]: https://github-readme-stats.vercel.app/api/pin/?username=visnkmr&repo=perlink
[osk]: https://github-readme-stats.vercel.app/api/pin/?username=visnkmr&repo=onscreenkeyboard
[graph]: https://github-readme-activity-graph.vercel.app/graph?username=visnkmr&theme=react-dark&hide_border=false&area=true
[bapl]:https://github-readme-stats.vercel.app/api/pin/?username=visnkmr&repo=backgroundappslist
[fx]:https://github-readme-stats.vercel.app/api/pin/?username=visnkmr&repo=file_explorer
[nk]:https://github-readme-stats.vercel.app/api/pin/?username=visnkmr&repo=nokeyboard
[nst]:https://github-readme-stats.vercel.app/api/pin/?username=visnkmr&repo=netspeed-test
[pm]:https://github-readme-stats.vercel.app/api/pin/?username=visnkmr&repo=powermenu
[tn]:https://github-readme-stats.vercel.app/api/pin/?username=visnkmr&repo=takenotes
[tns]:https://github-readme-stats.vercel.app/api/pin/?username=visnkmr&repo=timenetspeed
[wfm]:https://github-readme-stats.vercel.app/api/pin/?username=visnkmr&repo=wfm
[nspc]:https://github-readme-stats.vercel.app/api/pin/?username=visnkmr&repo=netspeed_pc
[fgpt]:https://github-readme-stats.vercel.app/api/pin/?username=visnkmr&repo=filegpt-filedime
