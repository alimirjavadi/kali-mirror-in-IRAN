# kali-mirror-in-IRAN

## Mirror Kali Repo

این مخزن آینه‌ی رسمی Kali است برای دانلود بسته‌ها از طریق ترمینال.  
فایل `/etc/apt/sources.list` را با محتوای زیر جایگزین کنید:

```bash
# See: https://www.kali.org/docs/general-use/kali-linux-sources-list-repositories/
# deb http://http.kali.org/kali kali-rolling main contrib non-free
# deb http://http.kali.org/kali kali-experimental main contrib non-free

# Additional line for source packages
# deb-src http://http.kali.org/kali kali-rolling main contrib non-free
# deb-src http://http.kali.org/kali kali-rolling main contrib non-free

deb http://ftp.halifax.rwth-aachen.de/kali/ kali-rolling main contrib non-free
deb http://ftp.halifax.rwth-aachen.de/kali/ kali-experimental main contrib non-free
deb-src http://ftp.halifax.rwth-aachen.de/kali/ kali-experimental main contrib non-free
deb-src http://ftp.halifax.rwth-aachen.de/kali/ kali-rolling main contrib non-free
deb http://ftp.halifax.rwth-aachen.de/kali/ kali-bleeding-edge main contrib non-free
```


سپس دستورات زیر را اجرا کنید:

```bash
sudo apt update
sudo apt upgrade
```

## Support

If this repository helped you, please consider giving it a ⭐ on GitHub. It helps others discover the project and motivates further improvements.

Thank you for your support!
