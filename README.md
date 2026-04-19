# Signal Library

100 long-form podcasts compressed to ~5 minutes each by [Signal](https://github.com/yimjason01-blip) — fidelity-preserving, first-person, speaker-attributed.

**Live site:** https://yimjason01-blip.github.io/signal-library/

## How it works

For each episode:
1. Fetch the original mp3 from the show's CDN
2. Transcribe with OpenAI Whisper (segment timestamps preserved)
3. Compress with Claude Sonnet 4.5 using a fidelity-preserving prompt (speaker voices, exact quotes on specifics, chronological flow)
4. Synthesize with Grok's "leo" voice
5. Cap at 5 minutes output (tight preset)

## Shows included

Dwarkesh Podcast · Lex Fridman Podcast · Huberman Lab · The Peter Attia Drive · All-In · Acquired · Invest Like the Best · My First Million · The Knowledge Project · Founders · The Tim Ferriss Show · Modern Wisdom · No Priors · Latent Space · How I Built This · FoundMyFitness · The Rich Roll Podcast · Business Breakdowns · Naval · The Art of Accomplishment
