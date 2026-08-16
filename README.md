# Kids Dua — recited translations

Synthesised Urdu and English audio for the Kids Dua app. Rendered offline by
`tools/render_audio.py` in the app repo; no speech model ships in the app.

**This audio is synthesised, not recited by a person.**

**Arabic is deliberately absent.** A general TTS voice reading Quranic Arabic has
no tajweed and no waqf. Arabic recitation, if it ever ships, comes from a human reciter.

## Voices

| Language | Voice | Licence |
|---|---|---|
| Urdu | ur_PK-fasih-medium | MIT |
| English | en_US-joe-medium | CC0 |

Both are Piper VITS voices from rhasspy/piper-voices.

## Layout

Per dua and language, `<dua_id>.<language>.m4a` (AAC-LC, mono, 22.05 kHz, 32 kbps)
and `<dua_id>.<language>.json` with per-line start/end seconds for highlighting.

Every file is under 20 MB, the largest jsDelivr will serve.

Consume via a pinned tag, never a branch: jsDelivr edge-caches a branch for
twelve hours with no way to withdraw a bad push.

## Contents

### Duas — 40 duas, 204 MB

- `dua_kumayl` — 7.7 MB
- `dua_tawassul` — 4.0 MB
- `hadith_kisa` — 4.0 MB
- `dua_ahad` — 2.5 MB
- `dua_sabah` — 3.8 MB
- `dua_nudba` — 9.2 MB
- `dua_jawshan_kabeer` — 30.9 MB
- `dua_jawshan_sagheer` — 11.1 MB
- `dua_abu_hamza_thumali` — 19.3 MB
- `dua_iftetah` — 6.3 MB
- `dua_simaat` — 5.3 MB
- `dua_mashlool` — 6.7 MB
- `dua_makarimul_akhlaq` — 6.4 MB
- `dua_mujeer` — 6.5 MB
- `dua_adeelah` — 3.3 MB
- `dua_yastashir` — 3.2 MB
- `dua_attawbah` — 4.6 MB
- `dua_asharaat` — 5.6 MB
- `dua_aaliya_madhaameen` — 5.4 MB
- `dua_faraj` — 0.6 MB
- `dua_wahdah` — 0.4 MB
- `dua_bahaa` — 2.2 MB
- `dua_wida` — 2.6 MB
- `dua_umm_dawood` — 7.4 MB
- `dua_al_hujjah` — 0.4 MB
- `dua_hujjat` — 0.3 MB
- `dua_saif_al_sagheeral_qamoos` — 1.3 MB
- `dua_of_imam_hussain` — 1.3 MB
- `dua_of_imam_hussain_2` — 0.8 MB
- `a_gift_from_imam_hussain` — 0.3 MB
- `dua_of_maqatil_bin_sulayman` — 0.4 MB
- `dua_arafah_imam_hussain` — 22.1 MB
- `dua_alqama` — 5.3 MB
- `dua_mubahila_day` — 5.3 MB
- `jafare_tayyar` — 5.5 MB
- `dua_sahar` — 0.6 MB
- `dua_for_the_betterment_of_society` — 0.8 MB
- `ayat_ulkursi` — 0.4 MB
- `ayat_ulmulk_32627` — 0.2 MB
- `ayat_ushshahadah_31819` — 0.2 MB

### Ziyarat — 2 duas, 1 MB

- `ziyarat_after_salat` — 0.4 MB
- `taqib_after_tasbih_zahra` — 0.7 MB

### Sahifa Sajjadiya — 68 duas, 137 MB

- `sahifa_dua_1` — 3.7 MB
- `sahifa_dua_2` — 1.3 MB
- `sahifa_dua_3` — 2.2 MB
- `sahifa_dua_4` — 1.6 MB
- `sahifa_dua_5` — 1.4 MB
- `sahifa_dua_6` — 2.4 MB
- `sahifa_dua_7` — 1.2 MB
- `sahifa_dua_8` — 1.3 MB
- `sahifa_dua_9` — 0.9 MB
- `sahifa_dua_10` — 0.9 MB
- `sahifa_dua_11` — 0.9 MB
- `sahifa_dua_12` — 1.7 MB
- `sahifa_dua_13` — 1.8 MB
- `sahifa_dua_14` — 1.7 MB
- `sahifa_dua_15` — 1.0 MB
- `sahifa_dua_16` — 3.1 MB
- `sahifa_dua_17` — 2.2 MB
- `sahifa_dua_18` — 0.4 MB
- `sahifa_dua_19` — 0.9 MB
- `sahifa_dua_20` — 5.7 MB
- `sahifa_dua_21` — 2.5 MB
- `sahifa_dua_22` — 2.7 MB
- `sahifa_dua_23` — 1.8 MB
- `sahifa_dua_24` — 2.7 MB
- `sahifa_dua_25` — 2.6 MB
- `sahifa_dua_26` — 1.0 MB
- `sahifa_dua_27` — 4.2 MB
- `sahifa_dua_28` — 1.0 MB
- `sahifa_dua_29` — 0.6 MB
- `sahifa_dua_30` — 1.0 MB
- `sahifa_dua_31` — 4.5 MB
- `sahifa_dua_32` — 5.0 MB
- `sahifa_dua_33` — 0.7 MB
- `sahifa_dua_34` — 0.8 MB
- `sahifa_dua_35` — 0.9 MB
- `sahifa_dua_36` — 1.2 MB
- `sahifa_dua_37` — 2.4 MB
- `sahifa_dua_38` — 0.6 MB
- `sahifa_dua_39` — 2.4 MB
- `sahifa_dua_40` — 0.8 MB
- `sahifa_dua_41` — 0.6 MB
- `sahifa_dua_42` — 4.7 MB
- `sahifa_dua_43` — 1.4 MB
- `sahifa_dua_44` — 3.9 MB
- `sahifa_dua_45` — 7.8 MB
- `sahifa_dua_46` — 2.7 MB
- `sahifa_dua_47` — 10.6 MB
- `sahifa_dua_48` — 5.5 MB
- `sahifa_dua_49` — 3.0 MB
- `sahifa_dua_50` — 1.4 MB
- `sahifa_dua_51` — 2.3 MB
- `sahifa_dua_52` — 2.0 MB
- `sahifa_dua_53` — 0.9 MB
- `sahifa_dua_54` — 1.6 MB
- `dua_sunday` — 1.0 MB
- `dua_monday` — 1.1 MB
- `dua_tuesday` — 0.9 MB
- `dua_wednesday` — 0.9 MB
- `dua_thursday` — 0.9 MB
- `dua_friday` — 0.9 MB
- `dua_saturday` — 0.7 MB
- `dua_55_sahifat_sajjadiyyah` — 0.8 MB
- `dua_56_sahifat_sajjadiyyah` — 1.4 MB
- `dua_57_sahifat_sajjadiyyah` — 0.4 MB
- `dua_58_sahifat_sajjadiyyah` — 0.6 MB
- `dua_59_sahifat_sajjadiyyah` — 1.6 MB
- `dua_60_sahifat_sajjadiyyah` — 1.0 MB
- `dua_61_sahifat_sajjadiyyah` — 0.9 MB

### Munajat — 18 duas, 27 MB

- `munajat_kufa` — 1.9 MB
- `munajat_shabaniya` — 4.3 MB
- `munajat_1_sahifat_sajjadiyyah` — 1.6 MB
- `munajat_2_sahifat_sajjadiyyah` — 1.1 MB
- `munajat_3_sahifat_sajjadiyyah` — 1.2 MB
- `munajat_4_sahifat_sajjadiyyah` — 1.3 MB
- `munajat_5_sahifat_sajjadiyyah` — 1.4 MB
- `munajat_6_sahifat_sajjadiyyah` — 1.3 MB
- `munajat_7_sahifat_sajjadiyyah` — 0.9 MB
- `munajat_8_sahifat_sajjadiyyah` — 1.5 MB
- `munajat_9_sahifat_sajjadiyyah` — 1.4 MB
- `munajat_10_sahifat_sajjadiyyah` — 0.8 MB
- `munajat_11_sahifat_sajjadiyyah` — 1.4 MB
- `munajat_12_sahifat_sajjadiyyah` — 1.2 MB
- `munajat_13_sahifat_sajjadiyyah` — 1.1 MB
- `munajat_14_sahifat_sajjadiyyah` — 1.1 MB
- `munajat_15_sahifat_sajjadiyyah` — 0.8 MB
- `munajat_of_imam_ali` — 2.6 MB

### Taqibat — 6 duas, 15 MB

- `taqibat_fajr_combined` — 6.6 MB
- `taqibat_dhuhr_combined` — 0.8 MB
- `taqibat_asr_combined` — 0.6 MB
- `taqibat_maghrib_combined` — 2.7 MB
- `taqibat_isha_combined` — 3.9 MB
- `friday_taqibat` — 0.5 MB

### Daily Duas — 22 duas, 3 MB

- `dua_upon_waking_up` — 0.1 MB
- `after_waking_up_3190194` — 0.4 MB
- `dua_after_rising_from_your_bed` — 0.1 MB
- `dua_before_sleeping` — 0.2 MB
- `dua_when_going_to_bed_18110` — 0.1 MB
- `salawaat_when_going_to_bed` — 0.1 MB
- `dua_before_meals` — 0.3 MB
- `dua_after_meals` — 0.1 MB
- `dua_1_when_leaving_home` — 0.1 MB
- `dua_2_when_leaving_home` — 0.0 MB
- `dua_when_in_the_washroom` — 0.1 MB
- `dua_when_combing_hair` — 0.1 MB
- `dua_when_combing_hair_202526` — 0.1 MB
- `dua_when_looking_into_the_mirror` — 0.1 MB
- `dua_when_wearing_clothes` — 0.1 MB
- `dua_when_wearing_new_clothes` — 0.2 MB
- `dua_when_wearing_shoes` — 0.1 MB
- `dua_when_lights_are_turned_off` — 0.0 MB
- `dua_in_the_evening` — 0.2 MB
- `dua_for_dawn_and_dusk` — 0.2 MB
- `dua_before_reciting_the_quran` — 0.4 MB
- `dua_after_reciting_the_quran` — 0.2 MB

---

**156 duas, 387 MB total.**
