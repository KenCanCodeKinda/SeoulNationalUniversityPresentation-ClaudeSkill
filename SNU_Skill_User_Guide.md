# SNU Presentation Style Skill - User Guide

## What This Skill Does

This skill helps Claude create professional academic presentations following the Seoul National University (SNU) design language. It includes:

- **Clean, professional Korean academic style**
- **Navy blue color scheme** (#0e4a84, #0f0f70, #898c8e)
- **Section-based organization** with numbering (01, 02, 03...)
- **Support for PowerPoint, Google Slides, and Canva**

## What's Included

### 1. SKILL.md
The main instruction file that tells Claude:
- When to use this skill
- How to create presentations for different platforms (PowerPoint, Google Slides, Canva)
- Design patterns and elements
- Quality checklist

### 2. references/design_specifications.md
Comprehensive design guide with:
- Complete color palette and usage guidelines
- Typography specifications (fonts, sizes, styling)
- Layout structures for different slide types
- Platform-specific guidelines
- Design principles

### 3. assets/snu_template.pptx
Your original presentation template that can be:
- Used as a starting point for PowerPoint presentations
- Referenced for design patterns
- Copied and modified programmatically

## How to Install

1. Download the `snu-presentation-style.zip` file
2. In Claude.ai, click the tools/settings menu
3. Navigate to Skills section
4. Upload the zip file

## How to Use

Once installed, simply ask Claude to create presentations:

**Examples:**
- "Create a PowerPoint presentation about climate change in SNU style"
- "Make a Google Slides presentation for my research proposal using the SNU template"
- "Design a Canva presentation following the SNU academic format"
- "Create slides with section numbering for my thesis defense"

Claude will automatically:
- Apply the correct colors (#0e4a84, #0f0f70, #898c8e)
- Use appropriate fonts (Rix고딕 B for Korean, with fallbacks)
- Structure content with section numbering
- Create emphasis boxes for key points
- Follow academic formatting conventions

## Platform Options

**Microsoft PowerPoint (.pptx)**
- Best option for full template support
- Claude can create files directly
- Uses python-pptx library or template modification

**Google Slides**
- Cloud-based option
- Claude provides detailed setup instructions
- Uses Noto Sans KR or Nanum Gothic fonts (substitutes for Rix고딕 B)

**Canva**
- Design-focused option
- Claude describes design elements for manual creation
- Good for visual customization

## Design Features

### Color Palette
- **Dark Navy Blue** (#0e4a84): Headers, section numbers
- **Deep Blue** (#0f0f70): Emphasis boxes, highlights
- **Medium Gray** (#898c8e): Secondary text

### Typography
- Titles: 35pt
- Headers: 22-24pt
- Body: 18-20pt
- Emphasis boxes: 16pt

### Section Numbering
Standard academic sections:
- 01 - 서론 (Introduction)
- 02 - 기존문헌 검토 (Literature Review)
- 03 - 가설 개발 (Hypothesis Development)
- 04 - 방법론 (Methodology)
- 05 - 실증분석 (Empirical Analysis)
- 06 - 결론 및 토의 (Conclusion & Discussion)

## Tips for Best Results

1. **Be specific about content**: The more details you provide, the better
2. **Mention platform preference**: Specify PowerPoint, Google Slides, or Canva
3. **Request emphasis boxes**: For hypotheses, key findings, or important points
4. **Specify section structure**: If you have a custom section order

## Example Requests

"Create a 10-slide PowerPoint in SNU style about sustainable energy with sections for introduction, literature review, methodology, and results"

"Make a Google Slides presentation for my thesis defense with emphasis boxes for each hypothesis"

"Design a Canva presentation using the SNU academic template with navy blue accents"

## Need Help?

If Claude doesn't automatically use the skill, try being more explicit:
- "Use the SNU presentation style to create..."
- "Following the SNU template, make..."
- "Create a presentation in Korean academic format..."
