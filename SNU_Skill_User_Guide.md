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


# SNU Skill - MAJOR CORRECTIONS

## Critical Errors Fixed

### 1. Section Number Position - COMPLETELY WRONG
**❌ Before:** I said section numbers were in TOP RIGHT
**✅ After:** Section numbers are in TOP LEFT at position (0.51", 0.34")

This was a fundamental error that would have made all presentations look wrong!

### 2. Emphasis Box Color - COMPLETELY WRONG  
**❌ Before:** I said use blue (#0f0f70) for hypothesis boxes
**✅ After:** Use GRAY (#898c8e) for hypothesis boxes

Blue is only for accent elements, not emphasis boxes!

### 3. Color Usage - MISUNDERSTOOD
**❌ Before:**
- Dark Navy Blue (#0e4a84): headers, section numbers
- Deep Blue (#0f0f70): emphasis boxes, highlighted content  
- Medium Gray (#898c8e): secondary text

**✅ After:**
- Dark Navy Blue (#0e4a84): title slide branding/logo areas
- Deep Blue (#0f0f70): accent elements (vertical bar on title slide, special highlights)
- Medium Gray (#898c8e): emphasis boxes (hypotheses, key findings)

## Detailed Layout Corrections

### Title Slide Layout - NOW ACCURATE

**Added Missing Elements:**
- Blue vertical bar on left side: Position (0.79", 2.65"), Size 0.15" x 1.12", Fill #0f0f70
- Class/Conference name box: Position (0.97", 0.57"), blue text (#0f0f70)
- Email text box: Position (1.5", 4.29"), 15pt font

**Corrected Positions:**
- Date: (9.52", 5.57"), not generic "top right"
- Main title: (1.07", 2.43"), size 11.72" x 1.56"
- Author: (9.52", 4.29"), size 3.38" x 1.28"

### Content Slide Layout - NOW ACCURATE

**The Three Placeholders:**
1. Section Number: (0.51", 0.34"), size 0.88" x 0.71" - LEFT side!
2. Section Title: (1.38", 0.34"), size 11.3" x 0.65" - next to number
3. Content Area: (0.51", 1.28"), size 12.18" x 5.47"

**Visual Layout:**
```
  01   Introduction          ← Numbers on LEFT, not right!
  ─────────────────────
  
  Content area...
```

### Special Slide Variations - NOW DOCUMENTED

**Research Question Slides:**
- Blue horizontal bar: Position (0.51", 1.3"), size 12.18" x 0.14", color #0f0f70
- Blue text below: 20pt, color #0f0f70
- Used for highlighting research questions

### Hypothesis Boxes - NOW CORRECT

**Specifications:**
- Background: #898c8e (GRAY, not blue!)
- Text: White
- Font: Rix고딕 B, 16pt
- Position: (2.04", 5.89")
- Size: 9.11" x 0.95"

## What Was Preserved (Correct from Start)

✅ Slide dimensions: 13.33" x 7.50" (16:9)
✅ Font: Rix고딕 B for Korean text
✅ Font sizes: 35pt title, 22-24pt headers, 18-20pt body, 16pt emphasis
✅ Section numbering system: 01, 02, 03, etc.
✅ Standard academic sections: Introduction, Literature Review, Hypothesis Development, etc.

## Impact of Corrections

### Before Corrections:
- Would create slides with section numbers in wrong position
- Would use wrong colors for emphasis boxes
- Would not include key design elements like vertical bar
- Would misunderstand color system entirely

### After Corrections:
- Perfect alignment with actual template structure
- Correct color usage matching template
- All elements positioned accurately
- Complete understanding of design system

## Example: What Changed for a Typical Slide

### Before (WRONG):
```
                              ┌──────┐
                              │  01  │  ← Wrong position!
                              └──────┘
Introduction                           ← Title alone

[Blue box with hypothesis]             ← Wrong color!
```

### After (CORRECT):
```
  01   Introduction                    ← Correct position!
  ─────────────────────

  Content...

  [Gray box with hypothesis]           ← Correct color!
```

## Files Updated

1. **SKILL.md**: Complete rewrite of:
   - Section numbering system
   - Color palette and usage
   - Title slide layout
   - Content slide layout
   - Emphasis box specifications
   - Added special slide variations

2. **design_specifications.md**: Complete rewrite of:
   - Color palette and guidelines
   - Title slide specifications
   - Section header slide specifications
   - Section numbering implementation
   - Emphasis box specifications

## Verification

All corrections verified against actual template file:
- `/mnt/user-data/uploads/1760859732180_0__서울대_발표양식_4.pptx`
- Analyzed with python-pptx
- Extracted exact positions, sizes, colors, and fonts
- Documented all special elements and variations

## Result

The skill now accurately reflects the ACTUAL template design and will create presentations that look exactly like the SNU academic style.

