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
💀Hack-Me-if-You-Can💀 cd Desktop

💀Hack-Me-if-You-Can💀Desktop % mkdir  MySharpWPScanner

💀Hack-Me-if-You-Can💀Desktop % cd MySharpWPScanner

💀Hack-Me-if-You-Can💀MySharpWPScanner % git clone https://github.com/SujeetBci786/Mysharpwp-scan.git

💀Hack-Me-if-You-Can💀MySharpWPScanner % ls

Mysharpwp-scan

💀Hack-Me-if-You-Can💀MySharpWPScanner# cd Mysharpwp-scan

💀Hack-Me-if-You-Can💀MySharpWPScanner % touch Mysharpwp                      # Make permission 

💀Hack-Me-if-You-Can💀MySharpWPScanner % chmod +x ./Mysharpwp                 # Make executable

💀Hack-Me-if-You-Can💀Mysharpwp-scan#./Mysharpwp -h  

💀Hack-Me-if-You-Can💀Mysharpwp-scan#./mysharpwp scan -u http://example.com -t full

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
./Mysharpwp scan -u http://example.com

# Verbose mode
./Mysharpwp scan -u http://example.com -v

# Save results to file
./Mysharpwp scan -u http://example.com -o results.txt

# Mysharpwp-scan + save to file
./Mysharpwp scan -u http://example.com -v -o results.txt

```

## Advannce Usage
```bash

🔹 Full scan (WordPress + Technologies)
          
     ./Mysharpwp scan -u http://example.com -t full
        
🔹 WordPress vulnerability scan only
          
      ./Mysharpwp scan -u http://example.com -t wp
        
🔹 Technology detection scan only
          
      ./Mysharpwp scan -u http://example.com -t tech
        
🔹 Scan with verbose output
          
      ./Mysharpwp scan -u http://example.com -t full -v
        
🔹 Output to file
          
      ./Mysharpwp scan -u http://example.com -t full -o results.txt

```

## How to Install Dependencies
Users (or you) can install all dependencies with:

```bash

💀Hack-Me-if-You-Can💀Mysharpwp-scan#touch requirements.txt

💀Hack-Me-if-You-Can💀Mysharpwp-scan#pip3 install -r requirements.txt

💀Hack-Me-if-You-Can💀Mysharpwp-scan#chmod 644 requirements.txt

💀Hack-Me-if-You-Can💀Mysharpwp-scan#pip3 install -r requirements.txt

💀Hack-Me-if-You-Can💀Mysharpwp-scan#ls
```

## Contributors
- [@hacker_sujeet](https://x.com/hacker_sujeet)





