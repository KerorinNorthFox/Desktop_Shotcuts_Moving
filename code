import os, shutil, glob, time

ToPath = #move to folder
FromPath = #move from desktop
def movesc():
    shortcuts = []
    shortcuts = glob.glob('<Desktop full path>\\*lnk')
    print(shortcuts)
    time.sleep(1)
    if len(shortcuts) != 0:
        for shortcut in shortcuts:
            shutil.move(shortcut, ToPath)
        print("ショートカット移動完了")
    else:
        print("ショートカットはありません")

while(True):
    movesc()
    print("スキャン終了")
    time.sleep(5)
    print("--------------------------------------------------")
    print("五秒経過、再スキャン")
    time.sleep(1)
