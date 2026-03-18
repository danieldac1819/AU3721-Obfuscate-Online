# AU3721-Obfuscate-Online - AU3721 Script Optimizer

![Version](https://img.shields.io/badge/Version-Beta-blue)
![License](https://img.shields.io/badge/License-BSL--1.0-orange)
![AutoIt](https://img.shields.io/badge/AutoIt-3.3.16.1-green)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey)
![Build](https://img.shields.io/badge/Build-Passing-brightgreen)


## 📋 Mục lục
- [Giới thiệu](#-giới-thiệu)
- [Tính năng](#-tính-năng)
- [Yêu cầu hệ thống](#-yêu-cầu-hệ-thống)
- [Cài đặt](#-cài-đặt)
- [Hướng dẫn sử dụng](#-hướng-dẫn-sử-dụng)
- [Tích hợp Context Menu](#1-tích-hợp-context-menu)
- [Giao diện 2 bảng](#2-giao-diện-2-bảng-dual-panel)
- [Hỗ trợ đa màn hình](#3-hỗ-trợ-đa-màn-hình-multi-monitor)
- [Chế độ Console](#4-chế-độ-console-cli)
- [Ignore Directives](#5-ignore-directives)
- [Công cụ trực tuyến](#-công-cụ-trực-tuyến)
- [Mẹo & Thủ thuật](#-mẹo--thủ-thuật)
- [License](#-license)
- [Liên hệ](#-liên-hệ)

## 📌 Giới thiệu

**AU3721 Script Optimizer** là công cụ tối ưu hóa và bảo vệ mã nguồn AutoIt chuyên nghiệp, được phát triển bởi **721PC-Net Corporation**. Công cụ giúp mã nguồn AutoIt của bạn trở nên gọn nhẹ hơn, khó đọc hơn và bảo vệ logic xử lý khỏi việc sao chép trái phép.

Phiên bản **Beta** hiện tại đã được thử nghiệm trên nhiều dự án AutoIt lớn nhỏ và sẵn sàng cho môi trường phát triển chuyên nghiệp.

## ✨ Tính năng

| Tính năng | Mô tả |
|-----------|-------|
| 🛡️ **Bảo vệ đa tầng** | Nhiều chế độ obfuscation từ cơ bản đến nâng cao |
| 📦 **Tích hợp Context Menu** | Xử lý nhanh trực tiếp từ Windows Explorer |
| 🖥️ **Hỗ trợ đa màn hình** | Tối ưu không gian làm việc cho lập trình viên |
| 📝 **Quản lý danh sách hàm** | Bảo vệ có chọn lọc các hàm quan trọng |
| 🎯 **CLI Mode** | Tích hợp dễ dàng vào quy trình build tự động |
| 🌐 **Online Tools** | Bộ công cụ trực tuyến hỗ trợ xử lý nhanh |
| 💾 **Tự động lưu cấu hình** | Lưu trạng thái và vị trí cửa sổ |
| 🔄 **Xử lý hàng loạt** | Hỗ trợ xử lý nhiều file cùng lúc |

## 🌐 Công cụ trực tuyến miễn phí

Truy cập ngay các công cụ trực tuyến **KHÔNG CẦN CÀI ĐẶT**:

| Tool | Chức năng | Link | Trạng thái |
|------|-----------|------|------------|
| **au3Form** | Tạo form AutoIt nhanh | [https://au3form.itdev721.workers.dev/](https://au3form.itdev721.workers.dev/) | 🟢 Online |
| **au3Maker** | Tạo script AutoIt cơ bản | [https://au3maker.itdev721.workers.dev/](https://au3maker.itdev721.workers.dev/) | 🟢 Online |
| **AU3721 Obfuscate** | Obfuscate trực tuyến | [https://au3obfus.itdev721.workers.dev/](https://au3obfus.itdev721.workers.dev/) | 🟢 Online |


Giao diện phiên bản miễn phí trực tuyến:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/46483958-7a6a-4201-8b13-80bae27ad063" />

Giao diện phiên bản Premium Online
<img width="1920" height="1031" alt="ScreenShot_20260306191700" src="https://github.com/user-attachments/assets/56f9d732-a7a2-4382-92f5-c6e0cac7c659" />

Giao diện phiên bản Premium Offline
<img width="1030" height="797" alt="ScreenShot_20260306192747" src="https://github.com/user-attachments/assets/262534ce-5046-4576-aca6-64a76320515b" />

## 🔍 Ví dụ thực tế

Dưới đây là minh họa chi tiết quá trình **AU3721 Script Optimizer** xử lý mã nguồn AutoIt:

### 📝 Mã nguồn gốc (Before Obfuscation)

```autoit
#Region ;**** Directives created by AutoIt3Wrapper_GUI ****
#AutoIt3Wrapper_Outfile=demo1.exe
#EndRegion ;**** Directives created by AutoIt3Wrapper_GUI ****

Global Const $mb_ok = 0
Global Const $mb_okcancel = 1
Global Const $mb_abortretryignore = 2
Global Const $mb_yesnocancel = 3
Global Const $mb_yesno = 4
Global Const $mb_retrycancel = 5
Global Const $mb_canceltrycontinue = 6
Global Const $mb_help = 16384
Global Const $mb_iconnone = 0
Global Const $mb_iconstop = 16
Global Const $mb_iconerror = 16
Global Const $mb_iconhand = 16
Global Const $mb_iconquestion = 32
Global Const $mb_iconexclamation = 48
Global Const $mb_iconwarning = 48
Global Const $mb_iconinformation = 64
Global Const $mb_iconasterisk = 64
Global Const $mb_usericon = 128
Global Const $mb_defbutton1 = 0
Global Const $mb_defbutton2 = 256
Global Const $mb_defbutton3 = 512
Global Const $mb_defbutton4 = 768
Global Const $mb_applmodal = 0
Global Const $mb_systemmodal = 4096
Global Const $mb_taskmodal = 8192
Global Const $mb_default_desktop_only = 131072
Global Const $mb_right = 524288
Global Const $mb_rtlreading = 1048576
Global Const $mb_setforeground = 65536
Global Const $mb_topmost = 262144
Global Const $mb_service_notification = 2097152
Global Const $mb_rightjustified = $mb_right
Global Const $idtimeout = -1
Global Const $idok = 1
Global Const $idcancel = 2
Global Const $idabort = 3
Global Const $idretry = 4
Global Const $idignore = 5
Global Const $idyes = 6
Global Const $idno = 7
Global Const $idclose = 8
Global Const $idhelp = 9
Global Const $idtryagain = 10
Global Const $idcontinue = 11
MsgBox($mb_systemmodal, "Title", "This message box will timeout after 10 seconds or select the OK button." & @ScriptFullPath)
```


### 📝 Mã sau khi obfuscation (After Obfuscation)

```autoit
; ==================================================================
; AU3721 Script Optimizer - Output File
; Generated on: 18/03/2026 07:31:38
; ==================================================================

Global $0[74]
_a()
Global $1[_b(0)]
_7()
Global $2[_b(1)]
_5()
Global $3[_6(_b(2))]
_2()
Global $4[_6(_b(3))]
_0()
#AutoIt3Wrapper_Outfile=demo1.exe
Global Const $5 = 4096
_1(_6(_b(4)), $5, _3(_6(_b(4))), _3(_6(_b(3))) & @ScriptFullPath)
Func _0()
    $4[_6(_b(4))] = _3(_6(_b(5)))
EndFunc
Func _1($6, $7=Default, $8=Default, $9=Default, $a=Default, $b=Default, $c=Default, $d=Default, $e=Default, $f=Default, $g=Default, $h=Default, $i=Default, $j=Default, $k=Default, $l=Default, $m=Default, $n=Default, $o=Default, $p=Default, $q=Default)
Local $r = $4[$6]
    If StringLeft($r, _6(_b(3))) == _3(_6(_b(6))) Then Return Execute($r)
Local $s = $r & _3(_6(_b(7))), _
    $t[_6(_b(8))] = [$7, $8, $9, $a, $b, $c, $d, $e, $f, $g, $h, $i, $j, $k, $l, $m, $n, $o, $p, $q], _
    $u = True
    For $v = _6(_b(4)) To _6(_b(9))
        If $t[$v] = Default Then ExitLoop
        If Not $u Then $s &= _3(_6(_b(10)))
        If IsString($t[$v]) Then
            $s &= _3(_6(_b(11))) & StringReplace($t[$v], _3(_6(_b(11))), _3(_6(_b(12)))) & _3(_6(_b(11)))
        Else
            $s &= $t[$v]
        EndIf
        $u = False
    Next
    Return Execute($s & _3(_6(_b(13))))
EndFunc
Func _2()
    $3[_6(_b(4))] = _4(_8(_b(2)), _8(_b(3)), _6(_b(14)))
    $3[_6(_b(3))] = _4(_8(_b(4)), _8(_b(5)), _6(_b(14)))
    $3[_6(_b(5))] = _4(_8(_b(6)), _8(_b(7)), _6(_b(14)))
    $3[_6(_b(6))] = _4(_8(_b(8)), _8(_b(9)), _6(_b(14)))
    $3[_6(_b(7))] = _4(_8(_b(10)), _8(_b(11)), _6(_b(14)))
    $3[_6(_b(10))] = _4(_8(_b(12)), _8(_b(13)), _6(_b(14)))
    $3[_6(_b(11))] = _4(_8(_b(14)), _8(_b(1)), _6(_b(14)))
    $3[_6(_b(12))] = _4(_8(_b(15)), _8(_b(16)), _6(_b(14)))
    $3[_6(_b(13))] = _4(_8(_b(17)), _8(_b(18)), _6(_b(14)))
EndFunc
Func _3($v)
    Return $3[$v]
EndFunc
Func _4($w, $x, $y)
Local $z = Binary(_8(_b(19)) & $w), _
    $10 = Binary($x), _
    $11[_b(5)], _
    $12 = DllOpen(_8(_b(20))), _
    $13, _
    $14 = ($y < _b(21) Or $y == _b(22)) ? _b(3) : _b(23)
    $13 = DllCall($12, _8(_b(24)), _8(_b(25)), _8(_b(26)), _b(2), _8(_b(27)), _b(2), _8(_b(27)), _b(2), _8(_b(23)), $14, _8(_b(23)), _b(28))
    If Not $13[_b(2)] Then Return _8(_b(29))
    $11[_b(2)] = $13[_b(3)]
    $13 = DllCall($12, _8(_b(24)), _8(_b(30)), _8(_b(31)), $11[_b(2)], _8(_b(32)), _b(33), _8(_b(27)), _b(2), _8(_b(23)), _b(2), _8(_b(26)), _b(2))
    $11[_b(3)] = $13[_b(7)]
Local $15 = DllStructCreate(_8(_b(34)) & BinaryLen($10) & _8(_b(35)))
    DllStructSetData($15, _b(3), $10)
    DllCall($12, _8(_b(24)), _8(_b(36)), _8(_b(31)), $11[_b(3)], _8(_b(37)), $15, _8(_b(23)), DllStructGetSize($15), _8(_b(23)), _b(3))
    $13 = DllCall($12, _8(_b(24)), _8(_b(38)), _8(_b(31)), $11[_b(2)], _8(_b(32)), $y, _8(_b(31)), $11[_b(3)], _8(_b(23)), _b(3), _8(_b(26)), _b(2))
    $11[_b(4)] = $13[_b(7)]
    DllCall($12, _8(_b(24)), _8(_b(39)), _8(_b(31)), $11[_b(3)])
Local $16 = DllStructCreate(_8(_b(34)) & BinaryLen($z) + _b(40) & _8(_b(35)))
    DllStructSetData($16, _b(3), $z)
    $13 = DllCall($12, _8(_b(24)), _8(_b(41)), _8(_b(31)), $11[_b(4)], _8(_b(31)), _b(2), _8(_b(24)), True, _8(_b(23)), _b(2), _8(_b(37)), $16, _8(_b(42)), BinaryLen($z))
Local $17 = BinaryToString(BinaryMid(DllStructGetData(DllStructCreate(_8(_b(34)) & $13[_b(8)] + _b(3) & _8(_b(35)), DllStructGetPtr($16)), _b(3)), _b(3), $13[_b(8)]), _b(6))
    DllCall($12, _8(_b(24)), _8(_b(43)), _8(_b(31)), $11[_b(4)])
    DllCall($12, _8(_b(24)), _8(_b(44)), _8(_b(31)), $11[_b(2)], _8(_b(23)), _b(2))
    DllCall(_8(_b(45)), _8(_b(24)), _8(_b(46)), _8(_b(31)), $12)
    Return $17
EndFunc
Func _5()
    $2[_b(2)] = _4(_8(_b(47)), _8(_b(48)), _b(49))
    $2[_b(3)] = _4(_8(_b(50)), _8(_b(51)), _b(49))
    $2[_b(4)] = _4(_8(_b(52)), _8(_b(53)), _b(49))
    $2[_b(5)] = _4(_8(_b(54)), _8(_b(55)), _b(49))
    $2[_b(6)] = _4(_8(_b(56)), _8(_b(57)), _b(49))
    $2[_b(7)] = _4(_8(_b(58)), _8(_b(59)), _b(49))
    $2[_b(8)] = _4(_8(_b(60)), _8(_b(61)), _b(49))
    $2[_b(9)] = _4(_8(_b(62)), _8(_b(63)), _b(49))
    $2[_b(10)] = _4(_8(_b(64)), _8(_b(65)), _b(49))
    $2[_b(11)] = _4(_8(_b(66)), _8(_b(67)), _b(49))
    $2[_b(12)] = _4(_8(_b(68)), _8(_b(69)), _b(49))
    $2[_b(13)] = _4(_8(_b(70)), _8(_b(71)), _b(49))
    $2[_b(14)] = _4(_8(_b(72)), _8(_b(73)), _b(49))
EndFunc
Func _6($v)
    Return Number($2[Number($v)])
EndFunc
Func _7()
    $1[_b(2)] = _9("\u0034\u0033\u0034\u0046\u0036\u0030\u0033\u0042\u0036\u0036")
    $1[_b(3)] = _9("\u007A\u0067\u006E\u0064\u0032\u006D\u0065\u0064\u0038\u006A\u0065\u0069\u0062\u0070\u0064\u006A")
    $1[_b(4)] = _9("\u0030\u0038\u0038\u0045\u0032\u0033\u0043\u0032\u0032\u0042\u0039\u0030\u0037\u0038\u0042\u0046\u0042\u0036\u0034\u0031\u0046\u0030\u0041\u0042\u0045\u0042\u0041\u0036\u0034\u0032\u0034\u0031\u0034\u0037\u0030\u0037\u0032\u0042\u0035\u0044\u0036\u0043\u0043\u0044\u0042\u0037\u0045\u0038\u0031\u0042\u0039\u0032\u0037\u0041\u0041\u0046\u0031\u0030\u0038\u0043\u0033\u0041\u0045\u0044\u0033\u0044\u0031\u0031\u0042\u0037\u0037\u0037\u0043\u0041\u0036\u0036\u0030\u0035\u0046\u0034\u0035\u0046\u0034\u0034\u0034\u0045\u0046\u0046\u0036\u0042\u0041\u0045\u0045\u0034\u0041\u0031\u0032\u0045\u0043\u0041\u0030\u0031\u0041\u0032\u0044\u0033\u0031\u0036\u0035\u0038\u0042\u0045\u0039\u0042\u0032\u0036\u00" & _
        "35\u0030\u0034\u0033\u0036\u0032\u0033\u0046\u0037\u0037\u0044\u0036\u0037\u0039\u0041\u0032\u0039\u0035\u0039\u0042\u0036\u0045\u0044\u0030\u0032\u0031")
    $1[_b(5)] = _9("\u0030\u0033\u006F\u0070\u006F\u0067\u0061\u0033\u006E\u006D\u006B\u0037\u0061\u0039\u0067\u0066")
    $1[_b(6)] = _9("\u0034\u0045\u0037\u0041\u0035\u0030\u0043\u0039\u0035\u0042\u0039\u0038")
    $1[_b(7)] = _9("\u006E\u0075\u0062\u0061\u0034\u0067\u0078\u006F\u0065\u0031\u0074\u0033\u0033\u0077\u0031\u0037")
    $1[_b(8)] = _9("\u0042\u0046")
    $1[_b(9)] = _9("\u0030\u0074\u0035\u006F\u006E\u0075\u007A\u0032\u007A\u0069\u0077\u0061\u0076\u0065\u0062\u0034")
    $1[_b(10)] = _9("\u0031\u0030")
    $1[_b(11)] = _9("\u0035\u0030\u0033\u0039\u0079\u006A\u0072\u006D\u0061\u0075\u0078\u0035\u006F\u0037\u0061\u006E")
    $1[_b(12)] = _9("\u0031\u0034\u0043\u0039")
    $1[_b(13)] = _9("\u0063\u0076\u006B\u0075\u0071\u006A\u006D\u006B\u0033\u006B\u0078\u0074\u0067\u0074\u0037\u0066")
    $1[_b(14)] = _9("\u0039\u0037")
    $1[_b(1)] = _9("\u0073\u0075\u0078\u006C\u006F\u0079\u0071\u0031\u0064\u006B\u007A\u0072\u006E\u0067\u0037\u0068")
    $1[_b(15)] = _9("\u0032\u0033\u0032\u0046")
    $1[_b(16)] = _9("\u0069\u0064\u0065\u0078\u0067\u0065\u0063\u0063\u0077\u0036\u0039\u0038\u006D\u0064\u0074\u0071")
    $1[_b(17)] = _9("\u0043\u0036")
    $1[_b(18)] = _9("\u006A\u0074\u006E\u0078\u0031\u0073\u0063\u0063\u0062\u006B\u0036\u0072\u0079\u0062\u0066\u0036")
    $1[_b(19)] = _9("\u0030\u0078")
    $1[_b(20)] = _9("\u0061\u0064\u0076\u0061\u0070\u0069\u0033\u0032\u002E\u0064\u006C\u006C")
    $1[_b(24)] = _9("\u0062\u006F\u006F\u006C")
    $1[_b(25)] = _9("\u0043\u0072\u0079\u0070\u0074\u0041\u0063\u0071\u0075\u0069\u0072\u0065\u0043\u006F\u006E\u0074\u0065\u0078\u0074")
    $1[_b(26)] = _9("\u0068\u0061\u006E\u0064\u006C\u0065\u002A")
    $1[_b(27)] = _9("\u0070\u0074\u0072")
    $1[_b(23)] = _9("\u0064\u0077\u006F\u0072\u0064")
    $1[_b(29)] = _9("")
    $1[_b(30)] = _9("\u0043\u0072\u0079\u0070\u0074\u0043\u0072\u0065\u0061\u0074\u0065\u0048\u0061\u0073\u0068")
    $1[_b(31)] = _9("\u0068\u0061\u006E\u0064\u006C\u0065")
    $1[_b(32)] = _9("\u0075\u0069\u006E\u0074")
    $1[_b(34)] = _9("\u0062\u0079\u0074\u0065\u005B")
    $1[_b(35)] = _9("\u005D")
    $1[_b(36)] = _9("\u0043\u0072\u0079\u0070\u0074\u0048\u0061\u0073\u0068\u0044\u0061\u0074\u0061")
    $1[_b(37)] = _9("\u0073\u0074\u0072\u0075\u0063\u0074\u002A")
    $1[_b(38)] = _9("\u0043\u0072\u0079\u0070\u0074\u0044\u0065\u0072\u0069\u0076\u0065\u004B\u0065\u0079")
    $1[_b(39)] = _9("\u0043\u0072\u0079\u0070\u0074\u0044\u0065\u0073\u0074\u0072\u006F\u0079\u0048\u0061\u0073\u0068")
    $1[_b(41)] = _9("\u0043\u0072\u0079\u0070\u0074\u0044\u0065\u0063\u0072\u0079\u0070\u0074")
    $1[_b(42)] = _9("\u0064\u0077\u006F\u0072\u0064\u002A")
    $1[_b(43)] = _9("\u0043\u0072\u0079\u0070\u0074\u0044\u0065\u0073\u0074\u0072\u006F\u0079\u004B\u0065\u0079")
    $1[_b(44)] = _9("\u0043\u0072\u0079\u0070\u0074\u0052\u0065\u006C\u0065\u0061\u0073\u0065\u0043\u006F\u006E\u0074\u0065\u0078\u0074")
    $1[_b(45)] = _9("\u006B\u0065\u0072\u006E\u0065\u006C\u0033\u0032\u002E\u0064\u006C\u006C")
    $1[_b(46)] = _9("\u0043\u006C\u006F\u0073\u0065\u0048\u0061\u006E\u0064\u006C\u0065")
    $1[_b(47)] = _9("\u0037\u0038\u0039\u0032\u0032\u0041\u0046\u0037")
    $1[_b(48)] = _9("\u0071\u0074\u0062\u006F\u0065\u006E\u0061\u0068\u0034\u0034\u006A\u0031\u0066\u0077\u0033\u0038")
    $1[_b(50)] = _9("\u0031\u0043\u0045\u0034\u0042\u0042\u0030\u0036\u0032\u0042\u0039\u0043\u0038\u0035")
    $1[_b(51)] = _9("\u006F\u0069\u007A\u0031\u0030\u0064\u0035\u006B\u0034\u0035\u0033\u0073\u0064\u0072\u0038\u006D")
    $1[_b(52)] = _9("\u0046\u0037\u0046\u0031\u0033\u0041\u0042\u0041\u0035\u0032\u0035\u0041\u0037\u0032")
    $1[_b(53)] = _9("\u0063\u0066\u0070\u006E\u0074\u0076\u0072\u0062\u0068\u0030\u0075\u006D\u0077\u006C\u0061\u0037")
    $1[_b(54)] = _9("\u0044\u0037\u0038\u0034\u0038\u0046\u0034\u0032")
    $1[_b(55)] = _9("\u0079\u006E\u0035\u007A\u0037\u0032\u0075\u006D\u006D\u006B\u006D\u0073\u0036\u0033\u0036\u0076")
    $1[_b(56)] = _9("\u0032\u0039\u0033\u0031\u0041\u0033\u0043\u0045")
    $1[_b(57)] = _9("\u0070\u0031\u0067\u0039\u0069\u0033\u0065\u0079\u0075\u0034\u0073\u0078\u0033\u0063\u0072\u0036")
    $1[_b(58)] = _9("\u0037\u0030\u0034\u0033\u0031\u0030\u0033\u0035\u0041\u0045\u0037\u0041\u0035\u0042")
    $1[_b(59)] = _9("\u0033\u0067\u0039\u006D\u0070\u0064\u006B\u006D\u006D\u0072\u006F\u0062\u0031\u0036\u0071\u0036")
    $1[_b(60)] = _9("\u0036\u0046\u0043\u0039\u0033\u0039\u0037\u0033\u0033\u0045")
    $1[_b(61)] = _9("\u0073\u0033\u0073\u007A\u006A\u007A\u0066\u0078\u0070\u007A\u0068\u0036\u0075\u0032\u0065\u006F")
    $1[_b(62)] = _9("\u0037\u0036\u0031\u0039\u0033\u0045\u0043\u0043\u0039\u0039")
    $1[_b(63)] = _9("\u0075\u0079\u0036\u0073\u0035\u0073\u0039\u0070\u0034\u0072\u0078\u0034\u0038\u006C\u0066\u006C")
    $1[_b(64)] = _9("\u0032\u0035\u0046\u0038\u0046\u0046\u0030\u0045\u0039\u0046\u0034\u0041\u0038\u0030")
    $1[_b(65)] = _9("\u0072\u006E\u0061\u006E\u0079\u0068\u0076\u0067\u0032\u0079\u006C\u0076\u0077\u0070\u0079\u0039")
    $1[_b(66)] = _9("\u0043\u0042\u0033\u0033\u0034\u0036\u0038\u0042\u0041\u0030\u0030\u0043\u0045\u0036")
    $1[_b(67)] = _9("\u007A\u0037\u0032\u0035\u0069\u0074\u0035\u006C\u0032\u0065\u0067\u0073\u0070\u0062\u0073\u0031")
    $1[_b(68)] = _9("\u0036\u0030\u0039\u0035\u0036\u0034\u0034\u0045\u0037\u0037\u0042\u0041\u0035\u0041")
    $1[_b(69)] = _9("\u0070\u0030\u0031\u0069\u0031\u0079\u0036\u0069\u0075\u0035\u0037\u0039\u0036\u0036\u0032\u006A")
    $1[_b(70)] = _9("\u0037\u0046\u0038\u0043\u0037\u0030\u0037\u0038\u0033\u0041\u0037\u0038\u0033\u0033")
    $1[_b(71)] = _9("\u0034\u0038\u0072\u0071\u0065\u0072\u0061\u006B\u0039\u0068\u006E\u0033\u0037\u0035\u0069\u0064")
    $1[_b(72)] = _9("\u0032\u0042\u0033\u0031\u0038\u0039\u0034\u0036\u0039\u0036\u0038\u0046\u0037\u0046\u0036\u0030")
    $1[_b(73)] = _9("\u0070\u006F\u0070\u0071\u0030\u0075\u0073\u0075\u0074\u0037\u006C\u0078\u006A\u0061\u0076\u0035")
EndFunc
Func _8($k)
    Return $1[$k]
EndFunc
; ###OBF_IGNORE_START###
Func _9($u)
Local $18 = "", _
    $19 = StringRegExp($u, '\\u([0-9a-fA-F]{4})', 3)
    If IsArray($19) Then
        For $k = 0 To UBound($19) - 1
            $18 &= ChrW(Dec($19[$k]))
        Next
    EndIf
    Return $18
EndFunc
; ###OBF_IGNORE_END###
Func _a()
    $0[0] = _9("\u0036\u0037\u0074\u006D\u0070")
    $0[1] = _9("\u0031\u0033\u0061\u0075\u0074\u006F\u0069\u0074")
    $0[2] = _9("\u0030\u0076\u0061\u006C")
    $0[3] = _9("\u0031\u0061\u0075\u0074\u006F\u0069\u0074")
    $0[4] = _9("\u0032\u0074\u006D\u0070")
    $0[5] = _9("\u0033\u0061\u0075\u0074\u006F\u0069\u0074")
    $0[6] = _9("\u0034\u0074\u006D\u0070")
    $0[7] = _9("\u0035\u0078\u0079\u007A")
    $0[8] = _9("\u0036\u0061\u0075\u0074\u006F\u0069\u0074")
    $0[9] = _9("\u0037\u0061\u0075\u0074\u006F\u0069\u0074")
    $0[10] = _9("\u0038\u0061\u0075\u0074\u006F\u0069\u0074")
    $0[11] = _9("\u0039\u0061\u0075\u0074\u006F\u0069\u0074")
    $0[12] = _9("\u0031\u0030\u0076\u0061\u006C")
    $0[13] = _9("\u0031\u0031\u0076\u0061\u006C")
    $0[14] = _9("\u0031\u0032\u0061\u0075\u0074\u006F\u0069\u0074")
    $0[15] = _9("\u0031\u0034\u0078\u0079\u007A")
    $0[16] = _9("\u0031\u0035\u0078\u0079\u007A")
    $0[17] = _9("\u0031\u0036\u0074\u006D\u0070")
    $0[18] = _9("\u0031\u0037\u0061\u0075\u0074\u006F\u0069\u0074")
    $0[19] = _9("\u0031\u0038\u0078\u0079\u007A")
    $0[20] = _9("\u0031\u0039\u0078\u0079\u007A")
    $0[21] = _9("\u0030\u0078\u0036\u0036\u0030\u0045")
    $0[22] = _9("\u0030\u0078\u0036\u0038\u0030\u0031")
    $0[23] = _9("\u0032\u0034\u0061\u0075\u0074\u006F\u0069\u0074")
    $0[24] = _9("\u0032\u0030\u0078\u0079\u007A")
    $0[25] = _9("\u0032\u0031\u0061\u0075\u0074\u006F\u0069\u0074")
    $0[26] = _9("\u0032\u0032\u0074\u006D\u0070")
    $0[27] = _9("\u0032\u0033\u0061\u0075\u0074\u006F\u0069\u0074")
    $0[28] = _9("\u0030\u0078\u0046\u0030\u0030\u0030\u0030\u0030\u0030\u0030")
    $0[29] = _9("\u0032\u0035\u0061\u0075\u0074\u006F\u0069\u0074")
    $0[30] = _9("\u0032\u0036\u0076\u0061\u006C")
    $0[31] = _9("\u0032\u0037\u0076\u0061\u006C")
    $0[32] = _9("\u0032\u0038\u0061\u0075\u0074\u006F\u0069\u0074")
    $0[33] = _9("\u0030\u0078\u0038\u0030\u0030\u0033")
    $0[34] = _9("\u0032\u0039\u0074\u006D\u0070")
    $0[35] = _9("\u0033\u0030\u0074\u006D\u0070")
    $0[36] = _9("\u0033\u0031\u0061\u0075\u0074\u006F\u0069\u0074")
    $0[37] = _9("\u0033\u0032\u0061\u0075\u0074\u006F\u0069\u0074")
    $0[38] = _9("\u0033\u0033\u0076\u0061\u006C")
    $0[39] = _9("\u0033\u0034\u0078\u0079\u007A")
    $0[40] = _9("\u0031\u0030\u0030\u0030\u0076\u0061\u006C")
    $0[41] = _9("\u0033\u0035\u0078\u0079\u007A")
    $0[42] = _9("\u0033\u0036\u0061\u0075\u0074\u006F\u0069\u0074")
    $0[43] = _9("\u0033\u0037\u0061\u0075\u0074\u006F\u0069\u0074")
    $0[44] = _9("\u0033\u0038\u0074\u006D\u0070")
    $0[45] = _9("\u0033\u0039\u0076\u0061\u006C")
    $0[46] = _9("\u0034\u0030\u0074\u006D\u0070")
    $0[47] = _9("\u0034\u0031\u0076\u0061\u006C")
    $0[48] = _9("\u0034\u0032\u0061\u0075\u0074\u006F\u0069\u0074")
    $0[49] = _9("\u0032\u0036\u0036\u0032\u0035\u0078\u0079\u007A")
    $0[50] = _9("\u0034\u0033\u0076\u0061\u006C")
    $0[51] = _9("\u0034\u0034\u0076\u0061\u006C")
    $0[52] = _9("\u0034\u0035\u0074\u006D\u0070")
    $0[53] = _9("\u0034\u0036\u0074\u006D\u0070")
    $0[54] = _9("\u0034\u0037\u0074\u006D\u0070")
    $0[55] = _9("\u0034\u0038\u0076\u0061\u006C")
    $0[56] = _9("\u0034\u0039\u0078\u0079\u007A")
    $0[57] = _9("\u0035\u0030\u0061\u0075\u0074\u006F\u0069\u0074")
    $0[58] = _9("\u0035\u0031\u0074\u006D\u0070")
    $0[59] = _9("\u0035\u0032\u0074\u006D\u0070")
    $0[60] = _9("\u0035\u0033\u0078\u0079\u007A")
    $0[61] = _9("\u0035\u0034\u0074\u006D\u0070")
    $0[62] = _9("\u0035\u0035\u0074\u006D\u0070")
    $0[63] = _9("\u0035\u0036\u0061\u0075\u0074\u006F\u0069\u0074")
    $0[64] = _9("\u0035\u0037\u0078\u0079\u007A")
    $0[65] = _9("\u0035\u0038\u0078\u0079\u007A")
    $0[66] = _9("\u0035\u0039\u0076\u0061\u006C")
    $0[67] = _9("\u0036\u0030\u0074\u006D\u0070")
    $0[68] = _9("\u0036\u0031\u0078\u0079\u007A")
    $0[69] = _9("\u0036\u0032\u0076\u0061\u006C")
    $0[70] = _9("\u0036\u0033\u0074\u006D\u0070")
    $0[71] = _9("\u0036\u0034\u0076\u0061\u006C")
    $0[72] = _9("\u0036\u0035\u0074\u006D\u0070")
    $0[73] = _9("\u0036\u0036\u0078\u0079\u007A")
EndFunc
Func _b($k)
    Return Number($0[Number($k)])
EndFunc

```
