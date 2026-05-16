# NASA-SMAP-MSL-Integration
NASA SMAP/MSL Integration sathealth ai
python main_nasa.py                                    # default 6 channels
python main_nasa.py --channels A-1 D-1 D-11 --scale 1.0  # full size
python main_nasa.py --list-channels                    # all 30 channels
لو عايز الـ real data الكاملة
# تنزّل الـ .npy files الحقيقية:
git clone https://github.com/khundman/telemanom
# بعدين تحط train/ و test/ في data/
# والـ pipeline هيشتغل عليهم أوتوماتيك ✅
