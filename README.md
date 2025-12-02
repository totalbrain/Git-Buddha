
# git-buddha
### Achieve Perfect Project Structure Enlightenment

Tired of Git silently dropping your empty directories?  
Frustrated by messy folder structures full of forgotten temp folders?

**git-buddha** is not just a `.gitkeep` tool.  
It's a **digital zen master** for your project's soul.

```bash
git-buddha --zen
```
→ Sit back. Drink tea. Your project is now in harmony with the universe.

## Why git-buddha?

| Problem                        | git-buddha Solution                                      |
|--------------------------------|-----------------------------------------------------------|
| Empty folders disappear in Git | Smart `.gitkeep` / `README.md` with meaningful content   |
| No one knows why a folder exists | Auto-generated explanations: "This will hold user avatars" |
| Zombie folders never touched   | Detects folders inactive for 6+ months                  |
| Team disagrees on structure    | Enforce rules via `.gitkeep-rules.yml`                  |
| `.gitignore` blocks `.gitkeep` | Automatically adds `!/.gitkeep` exception               |

## Installation

```bash
# Save as git-buddha.py and make executable
curl -L https://github.com/yourname/git-buddha/raw/main/git-buddha.py -o git-buddha.py
chmod +x git-buddha.py
sudo mv git-buddha.py /usr/local/bin/git-buddha
```

Or run directly:
```bash
python3 git-buddha.py
```

## Usage

```bash
# Classic mode (current directory)
git-buddha

# Multiple directories
git-buddha src/ tests/ public/

# Zen Mode — No questions, pure enlightenment
git-buddha --zen

# Use README.md instead of .gitkeep
git-buddha --mode readme

# Generate beautiful project structure diagram
git-buddha --diagram

# Intelligent AI-like placeholders
git-buddha --mode ai

# Keep old .gitkeep files even if folder is now full
git-buddha --no-cleanup
```

## Output Files

After running:
- `.git-buddha.log` → Full enlightenment report
- `project-structure.txt` → Visual tree (if `--diagram`)
- Smart `.gitkeep` or `README.md` in every empty folder
- Updated `.gitignore` with `!/.gitkeep`

## Example .gitkeep Content

```markdown
# This directory will contain user-uploaded avatars
# Example: john-doe.jpg, profile-2025.png
# Created by git-buddha at 2025-12-02T10:30:00
```

## Pro Tips

```bash
# Add to your pre-commit hook
git-buddha --zen

# Run weekly via GitHub Actions
# → Fail PRs with empty unprotected folders
```

## Philosophy

> "Before enlightenment: chop wood, carry water.  
> After enlightenment: chop wood, carry water...  
> But with perfect folder structure."

— Ancient Git Master

## License

MIT © 2025 – Made with love, Python, and a little bit of cosmic wisdom.

---
**May your directories never be lost again.**
