# skazzah-web

A minimal, cyberpunk-inspired personal page with a terminal aesthetic.

## Features

- **Matrix-style background animation** with falling characters
- **Terminal interface** showcasing interests and skills
- **Responsive design** that works on mobile and desktop
- **Glowing cyberpunk aesthetics** with green/cyan color scheme
- **Zero dependencies** - pure HTML, CSS, and vanilla JavaScript

## What's Inside

The page features:
- Animated terminal with typed commands
- Matrix rain background effect
- Clean, mysterious presentation
- Focus areas: infrastructure, compliance, AI, and security
- "More info coming soon" placeholder for future updates

## Customization

### Modify Interests
Edit the terminal section to update your areas of focus:
```html
<div class="terminal-line">infrastructure | compliance | AI | security</div>
```

### Change Color Scheme for main page
Main colors are defined in CSS:
- Primary: `#00ff88` (green)
- Accent: `#00ffff` (cyan)
- Background: `#0a0e27` (dark blue)
- Warning: `#ffaa00` (orange)


# Password Security Education Tools

A collection of interactive web-based tools designed to educate users about password security, hash cracking, and attack methodologies.

##  Purpose

These tools demonstrate how attackers crack passwords and why strong password practices matter. All processing happens client-side in your browser, nothing is sent to any server.

## Tools:

### 1. Password Crack Simulator
**File:** `password-simulator.html`

An educational tool that analyses password patterns and shows how long they would take to crack using various attack methods.

**Features:**
- Pattern-based password analysis (no need to enter real passwords)
- Real password testing with security warnings
- Three attack simulation types:
  - **Brute Force Attack** - Tries every possible combination
  - **Dictionary Attack** - Tests common words and passwords
  - **Rule-Based Attack** - Applies mutations to dictionary words
- Configurable hardware (laptop CPU to distributed networks)
- Multiple hash algorithms (MD5, SHA-256, bcrypt, Argon2)
- Color-coded strength meter with time estimates
- Educational insights and recommendations

**Use Cases:**
- Understanding password complexity requirements
- Learning why length matters more than special characters
- Seeing real-world crack times for different patterns

---

### 2. Hash Cracker
**File:** `hash-cracker.html`

A live hash cracking simulator that attempts to hashes using various attack methods.

**Features:**
- **Create Your Own Hash** - Generate hashes from test passwords
- **Live Cracking** - Watch in real-time as the tool attempts to crack hashes
- Multiple attack methods:
  - Try All (Recommended) - Smart word variations
  - Dictionary Attack - Common passwords only
  - Numeric Brute Force - Number-only passwords
  - Alphabetic Brute Force - Letter-only passwords
- Progress tracking with attempts counter and speed
- Pre-loaded examples for quick testing
- Educational warnings about password reuse

**Use Cases:**
- Understanding how dictionary attacks work
- Seeing why common passwords are dangerous
- Learning about hash functions and their speeds

---

### 3. Dance Mode
**File:** `dance-mode.html`

A fun animated robot that dances! A playful easter egg to lighten the serious security content.

**Features:**
- Animated dancing robot with moving arms and legs
- Retro terminal aesthetic matching the other tools
- Pulsing lights and floating music notes
- Responsive design


## Important Disclaimers

### Educational Use Only
These tools are for **educational purposes only**. They demonstrate:
- How attackers attempt to crack passwords
- Why certain password practices are weak
- The importance of password complexity

### Security Warnings
- **All processing happens locally** in your browser
- No data is sent to any server
- No passwords are stored or logged
- **NEVER** enter real passwords you actually use
- Use test/example passwords only
- Only crack hashes you own or have permission to test

### Legal Notice
Unauthorised access to computer systems is illegal. These tools should only be used:
- For personal education
- On systems you own
- On hashes you created or have explicit permission to test
- In authorized security testing scenarios

## Technical Details

### Browser Compatibility
- **Recommended:** Chrome, Firefox, Safari, Edge (latest versions)
- **Required:** JavaScript enabled
- **APIs Used:** Web Crypto API (for SHA-256/SHA-1 hashing)

### Hash Rates
The simulator uses realistic hash rates based on:
- **Laptop CPU**: ~100M MD5/sec, ~50M SHA-256/sec
- **Desktop GPU**: ~5B MD5/sec, ~2B SHA-256/sec
- **GPU Cluster**: ~100B MD5/sec, ~50B SHA-256/sec
- **Distributed Network**: ~10T MD5/sec, ~5T SHA-256/sec

### Limitations
- MD5 hashing not supported in browser (Web Crypto API limitation)
- Hash cracking is simplified for educational purposes
- Attack simulations are accelerated for demonstration

## What You'll Learn

### Password Strength
- Why length matters more than complexity
- How adding one character multiplies security exponentially
- The danger of dictionary words in passwords
- Common patterns attackers look for

### Attack Methods
- **Brute Force**: Systematic trying of all combinations
- **Dictionary**: Testing common passwords and words
- **Rule-Based**: Applying mutations (password → p@ssw0rd, Password123)
- **Rainbow Tables**: Pre-computed hash lookups

### Hash Functions
- Difference between fast hashes (MD5, SHA-256) and slow hashes (bcrypt, Argon2)
- Why slow hashing is intentional for passwords
- How hardware affects cracking speed

## Educational Context

### For Students
- Learn about cryptographic hash functions
- Understand computational complexity
- See practical applications of security concepts

### For Security Awareness
- Demonstrate to users why password policies exist
- Show real-world consequences of weak passwords
- Motivate better password practices

### For Developers
- Example of client-side Web Crypto API usage
- Responsive design patterns
- Educational UX design

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

### Ideas for Contribution
- Additional attack methods
- More hash algorithms
- Improved educational content
- Accessibility improvements
- Translations


## Author

Created by skazzah


## Acknowledgments

- Hash rate estimates based on real-world benchmarks
- Dictionary attack wordlists based on common password research
- Inspired by educational security tools and awareness campaigns

---

**Remember:** Use these tools responsibly and only for educational purposes! 
