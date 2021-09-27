##Data Description
1. The given training corpus includes about 25 hours Mandarin talks and technical reports (remaining data will be released later), along with human transcribed Chinese text and English translation.

2. The acoustic speech corpora are mainly collected and authorized by the tndao.com, and partially from the Baidu Company. We ask the human translators to generate the transcriptions and the translations carefully.

3. The informal speaking utterances such as '嗯', '啊', '这个，这个' are recorded in the transcriptions, but we remove them in the translations.
##Data Usage
1. You are free to use any tools to segment the talk into small size segments, such as ``ffmpeg`` command or ``soundfile`` in the ``python`` package (sample code can be found in the `split_wav.py`).

2. We encourage the participants to investigate the End-to-End Speech Translation approaches, reporting the comparison between the pipeline methods.

If you have any questions, please feel free to send email to `xionghao05@baidu.com` for further discussion.