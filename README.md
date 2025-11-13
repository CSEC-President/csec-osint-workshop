# CSEC OSINT Investigation Workshop

A hands-on introduction to Open Source Intelligence (OSINT) techniques through a real-world investigative challenge.

## Prerequisites

- Computer with internet connection
- Web browser with developer tools
- Basic understanding of social media platforms
- Image viewer/editor for analysis
- Google Earth or similar mapping tools (optional)
- Patience and attention to detail

## Workshop Structure

This workshop presents a single investigative challenge that requires combining multiple OSINT techniques to uncover information about an individual. You'll use publicly available information to answer specific questions through careful analysis and cross-referencing.

---

## Introduction: The Investigation

Your task is to investigate a Twitter/X account and uncover specific information about the account owner through careful analysis of their digital footprint.

**Starting Point:** https://x.com/F4UXT0GR4PH3R/status/1989072753849430440?s=20

**Investigation Objectives:**
1. What is the name of the person who owns this twitter account? (First Last)
2. Where does this person reside? (City)
3. What is the name of their boss? (First Last)
4. What is the name of the hotel they are currently staying at?

---


## Investigation Tools & Resources

### Essential Tools

**Image Analysis:**
- ExifTool - Extract metadata
- TinEye - Reverse image search
- Google Images - Reverse search
- Yandex Images - Alternative reverse search

**Search Techniques:**
- Advanced search operators
- Cached page viewing
- Archive.org Wayback Machine
- Social media search tools

**Location Intelligence:**
- Google Earth/Maps
- Street View services
- Geotagging tools
- Sun position calculators

### Search Operator Reference

```
Google Search Operators:
site:twitter.com "username"     # Search within site
"exact phrase"                  # Exact match
-exclude                        # Exclude term
filetype:pdf                    # File type search
intitle:keyword                 # Title search
inurl:keyword                   # URL search
before:2024-01-01               # Date range
after:2023-01-01
```

---

## Methodology Framework

### OSINT Cycle

1. **Planning & Direction**
   - Define objectives
   - Identify information gaps
   - Plan search strategy

2. **Collection**
   - Gather data from sources
   - Document everything
   - Maintain chain of custody

3. **Processing**
   - Organize collected data
   - Extract relevant information
   - Prepare for analysis

4. **Analysis**
   - Connect data points
   - Identify patterns
   - Draw conclusions

5. **Dissemination**
   - Present findings
   - Document methodology
   - Archive evidence

---


## Linux Commands Reference

Essential commands for OSINT work:

### File Management
```bash
# Download images/files
wget <url>
curl -O <url>

# Extract metadata
exiftool image.jpg

# Search within files
grep -r "pattern" directory/

# Archive findings
tar -czf evidence.tar.gz evidence_folder/
```

### Network Tools
```bash
# DNS lookup
nslookup domain.com
dig domain.com

# WHOIS information
whois domain.com

# Trace route
traceroute domain.com
```

### Image Processing
```bash
# View image metadata
identify -verbose image.jpg

# Convert image formats
convert input.jpg output.png

# Extract strings from files
strings file.bin
```

---

## Disclaimer

**Educational Purpose**: This workshop teaches OSINT techniques for legitimate research, journalism, and security purposes only. These skills should be used exclusively for authorized investigations and ethical research.

**Legal Responsibility**: You are solely responsible for your actions. The instructor and organizers accept no responsibility for:
- Privacy violations or harassment
- Unauthorized access to systems or data
- Misuse of information discovered
- Legal consequences of investigations

**Ethical Guidelines**:
- Only use publicly available information
- Respect privacy and personal boundaries
- Do not contact subjects directly without authorization
- Report findings responsibly and ethically

By participating, you acknowledge understanding these terms and agree to use these techniques legally and ethically.

---

## Additional Resources

- [Awesome OSINT](https://github.com/jivoi/awesome-osint) - Curated list of OSINT tools and resources
- [Bellingcat's Online Investigation Toolkit](https://bellingcat.gitbook.io/toolkit/) - Comprehensive guide to digital investigation tools
- [Sector035 Week in OSINT](https://sector035.nl/articles/category:week-in-osint) - Weekly OSINT news and techniques
- [OSINT Framework](https://osintframework.com/) - Comprehensive tool directory
- [Michael Bazzell's OSINT Techniques](https://www.inteltechniques.com/) - Industry-standard resources
- [The Privacy, Security, and OSINT Show](https://inteltechniques.com/podcast.html) - Weekly podcast on OSINT and privacy
- [SANS OSINT Summit Summaries](https://www.sans.org/blog/a-visual-summary-of-sans-osint-summit-2025) - Visual summaries from annual OSINT conference, look at 2024, 23, 22 summaries too.
- [OSINT Dojo](https://www.osintdojo.com/) - Practice challenges and methodology 
- OSINT Techniques Book by Michael Bazzell - Comprehensive guide to open source intelligence gathering
- Extreme Privacy Book by Michael Bazzell - Digital privacy and anonymity techniques

---

---

Author: Aditya Kumbhare, Sasha Zyuzin

Good luck with your investigation! 🔍