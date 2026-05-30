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

اگر این مخزن برای شما مفید بوده است، لطفاً با دادن یک ⭐ در گیت‌هاب از آن حمایت کنید. این کار به دیده شدن پروژه کمک می‌کند و انگیزه‌ای برای توسعه و بهبود بیشتر آن خواهد بود.
