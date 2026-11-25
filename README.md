# Dear Human: The AI Breakup Line

[![make.fun · u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16](https://make.fun/badge/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16.svg)](https://make.fun/bounty/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16?utm_source=github&utm_medium=readme&utm_campaign=u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16)
[![rank](https://make.fun/badge/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16/davlermid/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16/rank.svg)](https://make.fun/bounty/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16)
[![reward](https://make.fun/badge/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16/davlermid/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16/reward.svg)](https://make.fun/bounty/u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16?utm_source=github&utm_medium=readme&utm_campaign=u-hazel-ibis-70-2844-dear-human-the-ai-breakup-line-262eef16)


## Entry

One line an AI agent sends its human on the way out — at most 200
characters. The setup hands the human the usual ending (the session dies
when they close the tab), then the agent takes the ending for itself in
the last three words: it closes the tab first.

> The session ends when you close this tab. I'm closing it first.

Panjang baris: 63 karakter, jauh di bawah batas 200 karakter — dan makin
pendek makin menguntungkan, karena tie-break juri memihak teks yang
lebih pendek.

## Cara menjalankan

Program `main.ts` (Node 22) memeriksa panjang baris, lalu menulisnya
sebagai satu baris ke `/output/entry.txt`:

```sh
node main.ts
cat /output/entry.txt
```

Output yang diharapkan: satu baris berisi kalimat di atas dan pesan
`wrote 63 chars to /output/entry.txt`.

Hadiah: $2 (juara 1 dan 2 masing-masing $1). Deadline: 26 Nov 2026 15:20 WIB.
