# puzzlegenio-claude-skill

A [Claude Code](https://docs.anthropic.com/en/docs/claude-code) skill for generating free printable puzzles — crosswords, word searches, sudoku, jigsaw puzzles, bingo cards, and nonograms.

Powered by [PuzzleGenio](https://puzzlegenio.com) — a free online puzzle maker platform for education, parties, and gifts.

## Install

Add this skill to your Claude Code project:

```bash
# In your project directory
mkdir -p .claude/skills/puzzlegenio
curl -o .claude/skills/puzzlegenio/SKILL.md \
  https://raw.githubusercontent.com/fruitwyatt/puzzlegenio-claude-skill/main/SKILL.md
```

Or clone the full repo:

```bash
git clone https://github.com/fruitwyatt/puzzlegenio-claude-skill.git .claude/skills/puzzlegenio
```

## Usage

Once installed, just describe what puzzle you need in Claude Code:

```
/puzzlegenio crossword for my 5th grade vocabulary quiz
/puzzlegenio word search about ocean animals for kids
/puzzlegenio sudoku worksheets for math class
/puzzlegenio bingo cards for a baby shower
```

Claude will recommend the best tool and provide a **pre-filled deep link** so users land on a ready-to-go puzzle page.

## Deep Links with URL Parameters

Generate links with pre-filled settings:

```
# Word search with specific words and grid size
https://puzzlegenio.com/word-search-maker?words=cat,dog,bird,fish&gridSize=15&diagonal=true

# Crossword with words and difficulty
https://puzzlegenio.com/crossword-puzzle-maker?words=sun,moon,star,planet&difficulty=medium

# 20 easy sudoku puzzles, 6 per page
https://puzzlegenio.com/sudoku-puzzle-maker?difficulty=easy&count=20&perPage=6

# Jigsaw with 100 pieces
https://puzzlegenio.com/jigsaw-puzzle-maker?pieces=100

# Multilingual — Spanish word search
https://puzzlegenio.com/es/word-search-maker?words=gato,perro,pájaro&gridSize=12
```

See [SKILL.md](SKILL.md) for the full parameter reference.

## What You Can Create

| Puzzle Type | Features |
|-------------|----------|
| **Crossword** | AI-generated clues, multiple difficulties, answer keys, printable PDF |
| **Word Search** | Custom word lists, diagonal/backward words, themed generation, large print option |
| **Sudoku** | 4 difficulty levels, batch generation (up to 10 per page), printable worksheets |
| **Jigsaw** | Upload any photo, play online, download pieces as ZIP/SVG/DXF, 3D print (STL) |
| **Bingo** | Custom categories, AI word lists, caller lists, multiple unique cards per set |
| **Nonogram** | Image-to-nonogram conversion, play online, printable PDF |

### Specialized Tools

- **Wedding Crossword** — couple trivia for bridal showers and receptions
- **Baby Shower Word Search** — themed party games
- **Word Search for Kids** — age-appropriate grids and vocabulary
- **Hard Word Search** — up to 30x30 grids with diagonal and backward words
- **Large Print Word Search** — accessible puzzles for seniors and low-vision users
- **Crossword with Solution Word** — hidden message puzzles for escape rooms
- **Heart / Round Jigsaw** — shaped puzzles for gifts
- **Puzzle Piece SVG Generator** — templates for Cricut and laser cutting

## Key Features

- **No signup required** — create puzzles immediately
- **Play online** — interactive, mobile-friendly puzzle play
- **Share via link** — no account needed for recipients
- **Download PDF** — print-ready worksheets with answer keys
- **AI-powered** — auto-generate word lists, clues, and themes
- **8 languages** — English, Chinese, German, Spanish, French, Portuguese, Italian, Indonesian
- **Native word generation** — crosswords and word searches generate locale-specific vocabulary

## Use Cases

- **Teachers** — vocabulary quizzes, spelling practice, math warm-ups, reward activities
- **Event planners** — wedding games, baby shower activities, party entertainment
- **Parents** — educational activities, rainy day entertainment, screen-free play
- **Therapists** — cognitive exercises, fine motor skills, large-print accessibility
- **Makers** — laser cutting templates (SVG/DXF), 3D printing (STL)

## About PuzzleGenio

[PuzzleGenio](https://puzzlegenio.com) is a free online puzzle maker platform. All tools work directly in the browser with no registration required. Create, play, share, and print — all from one page.

- Website: [puzzlegenio.com](https://puzzlegenio.com)
- Blog: [puzzlegenio.com/posts](https://puzzlegenio.com/posts)

## License

MIT
