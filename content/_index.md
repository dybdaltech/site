---
title: Introduction
type: docs
---

# Welcome

{{< columns >}}
## Dybdaltech

A personal site for exploring tech and posting D&D stuff. 

<--->

## Hugo

This site is powered by Hugo, an awesome static site generator written in Go, I highly recommend checking it out. The theme used is Hugo-book.
{{< /columns >}}


## Tech?

Here's a piece of code that does something from my Reddit crawler..


```
    video_size = (640, 480)
    scraper_thread = threading.Thread(target=main_worker, args=(gui_queue,logger), daemon=True)
    #starting_path = sg.PopupGetFolder('Folder to display', default_path=settings.USER_SETTING['download_settings']['default_path'])
    starting_path = settings.USER_SETTING['download_settings']['default_path']
    treedata = folder_struct.add_files_in_folder('', starting_path)
    outputTab_layout = [
        [sg.Output(size=(80, 20), key='_OutputMany'), sg.Text(' Preview:'), sg.Image(data='', key='image_preview', size=(128, 128))] #TODO: Add watchlist here! And a enable/disable button?
    ]
```


