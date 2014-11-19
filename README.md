taskpaper
=========

TaskPaper major mode for emacs.  Based on major mode from https://github.com/jedthehumanoid/taskpaper.el

Put taskpaper.el file somewhere (for instance in ~/emacs.d/taskpaper.el)

In .emacs, add:  
   (load-file "~/taskpaper.el/taskpaper.el")  
   (require 'taskpaper-mode)

M-x taskpaper-mode to activate, or in .emacs:  
   (add-to-list 'auto-mode-alist '("\\.taskpaper\\'" . taskpaper-mode))  
for files with .taskpaper extension

   Keyboard shortcuts:  

| Shortcut  | Function  |
|:-:|:-:|
| S-return  | Focus project under cursor  |
| S-backspace  | Back to all projects  |
| C-c l  | Choose project from list  |
| C-c d   | Toggle done state of current task  |

| Shortcut  | Function  |  
|:-:|:-:|  
| S-return  | Focus project under cursor  |  


| S-backspace  | Back to all projects  |
| C-c l  | Choose project from list  |
| C-c d  | Toggle done state of current task  |
| C-c t  | Add @due tag with today's date to current task  |
| C-c a  | Move the current task to the Archive project (note, the Archive project must already exist)  |
| C-c z  | Move all tasks tagged with @done to the Archive project (note, the Archive project must already exist)  |