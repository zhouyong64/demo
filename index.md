# <center> Audio Demo for "Singing Voice Conversion for Severely Out-of-Tune Singings" </center>

## Abstract
This paper presents a method for correcting severely out-of-tune singing voices using a reference singing. Unlike some prior work where the correction can only be performed on mildly out-of-tune singings, we propose using a strong linguistic feature alone to do temporal alignment that can work even when the source singing is far off. As large changes in pitch can change the timbre of the voice, we propose a method for adjusting the pitch before applying pitch shifting algorithms. Our experiments show the proposed method can work on severely out-of-tune singings while achieving comparable performance on mildly out-of-tune singings as compared to prior work. The method also works in some cases where the source audio is a speaking voice, in effect doing a speech-to-singing conversion. 


## Comparison with Previous Work (mildy out-of-tune singings, in English and in Korean)
SET: Sangeon Yong and Juhan Nam, “Singing expression transfer from one voice to another for a given song,” in ICASSP. IEEE, 2018.
ours: Our proposed method

| source | reference | SET | ours | 
| :--- | :--- | :--- | :--- |
| <audio src="4songs/korean_paper_src/letItGo.mp3" controls preload></audio> | <audio src="4songs/korean_paper_ref/letItGo.mp3" controls preload></audio> | <audio src="4songs/korean_paper_other/letItGo.mp3" controls preload></audio> | <audio src="4songs/korean_paper_ours/letItGo.mp3" controls preload></audio> |
| <audio src="4songs/korean_paper_src/loveu.mp3" controls preload></audio> | <audio src="4songs/korean_paper_ref/loveu.mp3" controls preload></audio> | <audio src="4songs/korean_paper_other/loveu.mp3" controls preload></audio> | <audio src="4songs/korean_paper_ours/loveu.mp3" controls preload></audio> |
| <audio src="4songs/korean_paper_src/drunk.mp3" controls preload></audio> | <audio src="4songs/korean_paper_ref/drunk.mp3" controls preload></audio> | <audio src="4songs/korean_paper_other/drunk.mp3" controls preload></audio> | <audio src="4songs/korean_paper_ours/drunk.mp3" controls preload></audio> |
| <audio src="4songs/korean_paper_src/cherry.mp3" controls preload></audio> | <audio src="4songs/korean_paper_ref/cherry.mp3" controls preload></audio> | <audio src="4songs/korean_paper_other/cherry.mp3" controls preload></audio> | <audio src="4songs/korean_paper_ours/cherry.mp3" controls preload></audio> |
| --- | --- | --- | --- |

## Severely out-of-tune Singings in English

| source | reference | Corrected |
| :--- | :--- | :--- |
| <audio src="english_tests/src/middle3.mp3" controls preload></audio> | <audio src="english_tests/ref/middle3.wav" controls preload></audio> | <audio src="english_tests/ours_mp3/middle3.mp3" controls preload></audio> |
| <audio src="english_tests/src/lovein2.mp3" controls preload></audio> | <audio src="english_tests/ref/lovein2.wav" controls preload></audio> | <audio src="english_tests/ours_mp3/lovein2.mp3" controls preload></audio> |
| <audio src="english_tests/src/friend3.mp3" controls preload></audio> | <audio src="english_tests/ref/friend3.wav" controls preload></audio> | <audio src="english_tests/ours_mp3/friend3.mp3" controls preload></audio> |
| <audio src="english_tests/src/listen2.mp3" controls preload></audio> | <audio src="english_tests/ref/listen2.wav" controls preload></audio> | <audio src="english_tests/ours_mp3/listen2.mp3" controls preload></audio> |
| <audio src="english_tests/src/peace3.mp3" controls preload></audio> | <audio src="english_tests/ref/peace3.wav" controls preload></audio> | <audio src="english_tests/ours_mp3/peace3.mp3" controls preload></audio> |
| <audio src="english_tests/src/sunshine3.mp3" controls preload></audio> | <audio src="english_tests/ref/sunshine3.wav" controls preload></audio> | <audio src="english_tests/ours_mp3/sunshine3.mp3" controls preload></audio> |
| <audio src="english_tests/src/twinkle4.mp3" controls preload></audio> | <audio src="english_tests/ref/twinkle4.wav" controls preload></audio> | <audio src="english_tests/ours_mp3/twinkle4.mp3" controls preload></audio> |
| --- | --- | --- |

## Severely out-of-tune Singings in Mandarin

| source | reference | Corrected |
| :--- | :--- | :--- |
| <audio src="mandarin_tests/severe/src_mp3/l_girl_p1.mp3" controls preload></audio> | <audio src="mandarin_tests/severe/ref/l_girl_p1.wav" controls preload></audio> | <audio src="mandarin_tests/severe/res_mp3/l_girl_p1.mp3" controls preload></audio> |
| <audio src="mandarin_tests/severe/src_mp3/l_dxh_p1.mp3" controls preload></audio> | <audio src="mandarin_tests/severe/ref/l_dxh_p1.wav" controls preload></audio> | <audio src="mandarin_tests/severe/res_mp3/l_dxh_p1.mp3" controls preload></audio> |
| <audio src="mandarin_tests/severe/src_mp3/1word.mp3" controls preload></audio> | <audio src="mandarin_tests/severe/ref/1word.wav" controls preload></audio> | <audio src="mandarin_tests/severe/res_mp3/1word.mp3" controls preload></audio> |
| --- | --- | --- |

## Mildly out-of-tune Singings in Mandarin

| source | reference | Corrected |
| :--- | :--- | :--- |
| <audio src="mandarin_tests/mildly/src_mp3/f_eyes.mp3" controls preload></audio> | <audio src="mandarin_tests/mildly/ref/f_eyes.wav" controls preload></audio> | <audio src="mandarin_tests/mildly/res_mp3/f_eyes.mp3" controls preload></audio> |
| <audio src="mandarin_tests/mildly/src_mp3/10000.mp3" controls preload></audio> | <audio src="mandarin_tests/mildly/ref/10000.wav" controls preload></audio> | <audio src="mandarin_tests/mildly/res_mp3/10000.mp3" controls preload></audio> |
| --- | --- | --- |

## Speech-to-Singing Conversion in English

| source | reference | Converted |
| :--- | :--- | :--- |
| <audio src="read2sing_tests/src_mp3/ADIZ_13_1.mp3" controls preload></audio> | <audio src="read2sing_tests/ref/ADIZ_13_1.wav" controls preload></audio> | <audio src="read2sing_tests/ours_mp3/ADIZ_13_1.mp3" controls preload></audio> |
| <audio src="read2sing_tests/src_mp3/ADIZ_18_1.mp3" controls preload></audio> | <audio src="read2sing_tests/ref/ADIZ_18_1.wav" controls preload></audio> | <audio src="read2sing_tests/ours_mp3/ADIZ_18_1.mp3" controls preload></audio> |
| <audio src="read2sing_tests/src_mp3/JLEE_11_1.mp3" controls preload></audio> | <audio src="read2sing_tests/ref/JLEE_11_1.wav" controls preload></audio> | <audio src="read2sing_tests/ours_mp3/JLEE_11_1.mp3" controls preload></audio> |
| <audio src="read2sing_tests/src_mp3/ZHIY_03_1.mp3" controls preload></audio> | <audio src="read2sing_tests/ref/ZHIY_03_1.wav" controls preload></audio> | <audio src="read2sing_tests/ours_mp3/ZHIY_03_1.mp3" controls preload></audio> |
| <audio src="read2sing_tests/src_mp3/sunshine.mp3" controls preload></audio> | <audio src="read2sing_tests/ref/sunshine.wav" controls preload></audio> | <audio src="read2sing_tests/ours_mp3/sunshine.mp3" controls preload></audio> |
| <audio src="read2sing_tests/src_mp3/middle.mp3" controls preload></audio> | <audio src="read2sing_tests/ref/middle.wav" controls preload></audio> | <audio src="read2sing_tests/ours_mp3/middle.mp3" controls preload></audio> |
| --- | --- | --- |

## The Effects of Using Pitch Adjustment

| source | reference | w/o Pitch Adjustment | w/ Pitch Adjustment |
| :--- | :--- | :--- | :--- |
| <audio src="mandarin_tests/mildly/src_mp3/f_eyes.mp3" controls preload></audio> | <audio src="mandarin_tests/mildly/ref/f_eyes.wav" controls preload></audio> | <audio src="mandarin_tests/mildly/res_notAdjustF0_mp3/f_eyes.mp3" controls preload></audio> | <audio src="mandarin_tests/mildly/res_mp3/f_eyes.mp3" controls preload></audio> |
| --- | --- | --- | --- |

