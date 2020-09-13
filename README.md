# Line-Notify-1.0-Delphi-10.4
Line Notify คืออะไร Line Notify คือบริการที่ LINE ให้เราส่งข้อความ หรือแจ้งเตือนอัตโนมัติ ไม่ว่าจะส่งเข้าผ่าน Group หรือบัญชีส่วนตัว ผ่าน API ของ LINE โดยตรง 
Component delphi for 10.4 By REST delphi
AccessToken :
ImageFileNmae:
StickerId:
StickerPackageId
Text:

LINENotify1.AccessToken := ''; // TOKEN LINE
LINENotify1.Text := 'ข้อความ';
LINENotify1.stickerId := edtStickerID.Text;   //สติ๊กเกอร์ไอดี  ** ว่างได้ //' https://devdocs.line.me/files/sticker_list.pdf
LINENotify1.stickerPackageId := edtStickerPackageID.Text; //ติ๊กเกอร์แพคเกจไอดี  ***  ว่างได้
LINENotify1.imageFileName := edtImage.Text; //รูปภาพ  *** ว่างได้ C://image/img.png
LINENotify1.SendText;

