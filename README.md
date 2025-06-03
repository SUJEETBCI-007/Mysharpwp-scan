## MySharp WordPress Plugin Scanner

- A security tool to scan WordPress sites for vulnerable plugins and CVEs.

# MySharp WordPress Plugin Scanner

![MySharpWPScanner](https://github.com/user-attachments/assets/4db2af15-f8b5-4e74-9237-2f586edf8c74)


## Features
- Vulnerability scanning
- Verbose mode for detailed reports
- Export results to text files
- Customizable scanning options

## Requirements
- Python 3.x

## Installation

```bash
user@users-MacBook-Pro ~ % cd Desktop

user@users-MacBook-Pro Desktop % mkdir  MySharpWPScanner

user@users-MacBook-Pro Desktop % cd MySharpWPScanner

user@users-MacBook-Pro MySharpWPScanner % git clone https://github.com/SujeetBci786/Mysharpwp.git

user@users-MacBook-Pro MySharpWPScanner % touch Mysharpwp

user@users-MacBook-Pro ~ % chmod +x Mysharmwp                # Make executable
```

EOL
&& cat > requirements.txt << 'EOL'
# Python standard libraries only
# No additional packages required


### 4. Create Python Dependencies File (requirements.txt - optional)
- touch requirements.txt


## Should show:

```base
MySharpWPScanner/

-├── Mysharpwp

-├── README.md

-└── requirements.txt

```

### Test Your Setup

```base
# Basic scan
./wpprobe scan -u http://example.com

# Verbose mode
./wpprobe scan -u http://example.com -v

# Save results to file
./wpprobe scan -u http://example.com -o results.txt

# Verbose + save to file
./wpprobe scan -u http://example.com -v -o results.txt

```

## Advannce Usage
```bash

🔹 Full scan (WordPress + Technologies)
          
     ./mysharp scan -u http://example.com -t full
        
🔹 WordPress vulnerability scan only
          
      ./mysharp scan -u http://example.com -t wp
        
🔹 Technology detection scan only
          
      ./mysharp scan -u http://example.com -t tech
        
🔹 Scan with verbose output
          
      ./mysharp scan -u http://example.com -t full -v
        
🔹 Output to file
          
      ./mysharp scan -u http://example.com -t full -o results.txt

```


## Contributors
- [@hacker_sujeet](https://github.com/hacker_sujeet)





