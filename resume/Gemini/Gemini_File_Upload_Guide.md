# 📂 Using File Uploads Effectively with Gemini

Maximize the effectiveness of your interactions with Gemini by uploading relevant files directly into your conversation. This provides rich context for tasks like resume reviews and job description analysis.

## ✅ Recommended File Types for Upload

Gemini typically works well with common document formats. Prioritize files with selectable text:

- **PDF (.pdf)**: Excellent for sharing finalized resumes and job descriptions. Ensure the PDF contains actual text, not just images of text (test by trying to select/copy text).
- **Microsoft Word (.docx)**: Good for resumes that might need editing suggestions.
- **Plain Text (.txt)**: Simple and effective for raw text like Brag Docs or notes.
- **Markdown (.md)**: Good for structured text.

*(Support for other types like code files may vary)*

## 📁 What to Upload for Resume Help

Provide documents that give Gemini the context it needs:

- **Your Current Resume**: Essential for reviews, critiques, tailoring, and ATS checks.
- **Target Job Descriptions**: Allows Gemini to analyze requirements and identify keywords.
- **"Brag Document"**: Your raw list of accomplishments for Gemini to help refine into bullet points.
- **Cover Letter Drafts**: For review and refinement.

## 🚫 What to Avoid Uploading

- **Image-Based PDFs or Image Files (.jpg, .png):** Gemini primarily processes text. If the document is just a picture of words, it cannot effectively analyze the content.
- **Password-Protected Files:** Gemini cannot access protected documents.
- **Overly Large Files:** Extremely large documents might exceed processing limits.
- **Files with Complex/Broken Formatting:** Heavy use of unusual tables, columns, or graphics might hinder text extraction.

## 📝 Effective Prompt Examples After Uploading

Clearly tell Gemini how to use the files you've uploaded:

```
I've uploaded my current resume (`resume_v1.pdf`) and the job description (`target_role_jd.pdf`). Please review my resume based on this specific job description and suggest improvements for alignment and ATS optimization.
```

```
Using the uploaded Brag Document (`brag_doc.txt`), please help me draft impactful, quantified resume bullet points suitable for a [Target Role Title].
```

```
Compare my uploaded resume (`resume_final.docx`) against the three job descriptions I've also uploaded (`jd1.pdf`, `jd2.pdf`, `jd3.pdf`). Identify the common keywords I should be using and suggest which of my experiences best align with these roles.
```

🚀 **Best Practices**
- Verify Selectable Text: Before uploading PDFs, ensure you can select and copy the text within them.
- Be Explicit: Clearly state which uploaded file(s) Gemini should use for the specific task you're requesting.
- One Task at a Time: Focus prompts on a specific analysis using the uploaded files (e.g., "Review resume against JD," "Draft bullets from Brag Doc").

Use Gemini's file upload feature strategically to provide detailed context and get more accurate, relevant assistance.
