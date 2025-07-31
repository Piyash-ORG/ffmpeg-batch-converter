# FFmpeg Batch Converter

This script batch converts videos from `/sdcard/Download/HighS/` to 320x240 resolution using FFmpeg, and stores them in `/sdcard/Movies/HighS_Converted/`.  
Already converted files are skipped automatically.

---

## 🔧 Usage (Termux)

```bash
pkg install git ffmpeg -y
git clone https://github.com/Piyash-ORG/ffmpeg-batch-converter.git
cd ffmpeg-batch-converter
chmod +x convert.sh
./convert.sh
