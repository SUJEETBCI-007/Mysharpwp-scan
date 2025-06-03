# MySharp WordPress Plugin Scanner

![Scanner Banner](https://via.placeholder.com/800x200?text=MySharp+WordPress+Scanner)

A security tool to scan WordPress sites for vulnerable plugins and CVEs.

## Features
- Vulnerability scanning
- Verbose mode for detailed reports
- Export results to text files
- Customizable scanning options

## Installation
```bash
git clone https://github.com/SujeetBci786/Mysharmwp.git
cd MySharpWPScanner
chmod +x Mysharmwp  # Make executable

## Usage

# Basic scan
./wpprobe scan -u http://example.com

# Verbose mode
./wpprobe scan -u http://example.com -v

# Save results to file
./wpprobe scan -u http://example.com -o results.txt

# Verbose + save to file
./wpprobe scan -u http://example.com -v -o results.txt


## Requirements
- Python 3.x

### 4. Create Python Dependencies File (requirements.txt - optional)
⁠ bash
touch requirements.txt
 ⁠

Since this project only uses Python standard libraries, the file can be empty. But you can add:
⁠ txt
# Python standard libraries only
# No additional packages required
 ⁠

### Final Structure Verification
⁠ bash
tree MySharpWPScanner
 ⁠

Should show:

MySharpWPScanner/
├── wpprobe
├── README.md
└── requirements.txt


### Test Your Setup
⁠ bash
# Make executable
chmod +x wpprobe

# Run test scan
./wpprobe scan -u http://test.com

# Run verbose scan
./wpprobe scan -u http://test.com -v

# Save to file
./wpprobe scan -u http://test.com -o scan_results.txt
 ⁠
# MySharp WordPress Plugin Scanner

A security tool to scan WordPress sites for vulnerable plugins and CVEs.

## Features
- Vulnerability scanning
- Verbose mode for detailed reports
- Export results to text files
- Customizable scanning options

## Installation
 ⁠bash
git clone https://github.com/your-username/MySharpWPScanner.git
cd MySharpWPScanner
chmod +x wpprobe


⁠ ## Usage
 ⁠bash
# Basic scan
./wpprobe scan -u http://example.com

# Verbose mode
./wpprobe scan -u http://example.com -v

# Save results to file
./wpprobe scan -u http://example.com -o results.txt

# Verbose + save to file
./wpprobe scan -u http://example.com -v -o results.txt


## Requirements
- Python 3.x

## Contributors
- [@hacker_sujeet](https://github.com/hacker_sujeet)

EOL
&& cat > requirements.txt << 'EOL'
# Python standard libraries only
# No additional packages required
EOL
