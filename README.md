# Oral History Processing Guide
Cleveland Voices – also known as the Cleveland Regional Oral History Collection – is a project of the Center for Public History + Digital Humanities at Cleveland State University. Contributors to the Cleveland Voices project may refer to this document for information and guidance regarding various technical aspects. This guide does not deal with the theory or practice of oral history collection itself.

## Published Interviews
Interviews collected for this project are published in two places: the [Cleveland Voices](https://clevelandvoices.org/) website – optimized for use by the general public – and the [Engaged Scholarship @ CSU](https://engagedscholarship.csuohio.edu/crohc/) website – the university’s institutional repository, which serves as the longterm archive and is maintained by the CSU Library. In terms of process, the interviews are first published in full to the institutional repository and then select metadata is synced via [OAI-PMH](https://www.openarchives.org/pmh/) to Cleveland Voices. Original files are always served directly from the institutional repository. 

## Workspace and Storage
Interviews are backed up (among other places) in the Center’s OneDrive account, which is also used as a workspace for preparing interviews for publication. 

### Upload Area
We refer to the shared workspace as the Upload Area. Access to the Upload Area is granted as needed. When a new interview is collected, the requisite files will typically be uploaded here first. From there, a project administrator will coordinate the next steps toward publication. This space is also used to coordinate the transcription of existing interviews.

## File Requirements
When adding new interviews to the Upload Area, please closely follow these detailed guidelines. 

### Numeric Identifiers
Each interview is assigned a 6-digit numeric identifier. The first 3 digits represent the series and the next 3 digits represent the order in which the interview was accessioned. For example, `455` is the identifier for the Public Art series. As such, the third interview in the series would be assigned the identifier `455003`. This system ensures that each interview has a unique identifier within the collection. It can also be used to determine the provenance of the interview if it is misplaced, misfiled, or if its original context is otherwise lost.

### Required Files and File Names
Using the system for numeric identifiers described above, please upload new interviews to the Upload Area in a structured, named folder that follows the example below.

```
XXXXXX John Doe and Jane Doe (folder)
- XXXXXX John Doe and Jane Doe.mp3 (audio file)
- XXXXXX John Doe and Jane Doe.txt (audio transcript file)
- XXXXXX metadata.txt (metadata file)
- XXXXXX release.pdf (signed permission form file)
```

#### Folder
Name the folder with the numeric identifier followed by the name of the interviewee(s). Use spaces between each word (as opposed to dashes or underscores), omitting honorifics such as Misses/Mrs., Doctor/Dr., Sister/Sr., etc. You may include a middle name or initial if it is how the interviewee prefers to be identified or if it is useful for differentiating interviewees with similar names. 

The folder name you use here will be used in identical form for each interview file (with a couple exceptions).

Place all files for the interview inside this folder.

#### Audio Files
Give the audio file and/or video file the same name as the folder. The type of file will be inferred by the file extension. For instance, an audio file will typically have the extension of `.wav` or `.mp3`.

#### Transcript Files
Give the audio transcript file and/or video caption file the same name as the folder.

This file must be in plain text format (no formatting whatsoever is allowed) and must use the `.txt` file extension.

In most cases, a project administrator will create an AI-generated transcript/caption file on your behalf and upload it for you to proof and correct as needed. See Transcription Guidelines below.

#### Metadata File
Each interview must be accompanied by a metadata file that contains the following information: a formal title for the interview, the date of the interview, names and roles of each participant, the numeric identifier, keywords, and an abstract.  This metadata is used to record and publish the details of the interview.

Give this file a name that includes the numeric identifier, e.g. `XXXXXX metadata.txt`. 

This file must be in plain text format (no formatting whatsoever is allowed) and must use the `.txt` file extension.

Below is an example of a complete metadata file:

```
Title:
John Smith interview, 31 December 1999

Participants:
Smith, John (interviewee)
Doe, Jane (interviewer)
Doe, John (facilitator)

Date:
31 December 1999

Abstract:
Father John R. Smith discusses his experiences growing up in an Yugoslav immigrant community during the 1950s and 1960s, including his parents' emigration from post-WWII Yugoslavia and his childhood navigating between Yugoslav traditions at home and American culture in public schools. He reflects on the close-knit ethnic community centered around the parish church, ethnic social clubs, and language schools, describing how his generation balanced cultural preservation with integration into American society. Smith also addresses his decision to enter seminary in the late 1960s, his formation during the post-Vatican II period, his 1973 ordination, and his current daily responsibilities at St. Vladimir, including pastoral care and his continuing involvement with the US' evolving Eastern European community as the twentieth century draws to a close.

Keywords: 
Yugoslavia, St. Vladimir, religion, Catholicism, WWII, immigration, race and ethnicity, assimilation
```

- Take note of the **Title** format used in the example above. The date in the title should be formatted as DD Month YYYY. Note that the title should not include honorifics such as Dr. (refer to folder and file naming guidelines above).
- **Participant** names should be listed in inverted form (last name first) followed by the parenthetical role. Common roles include interviewee, interviewer, facilitator, and participant (the latter for individuals who are present in the recording but whose participation was incidental).
- The **Abstract** should be approximately one paragraph in length (3-6 sentences) and should broadly describe the interview contents using objective language suitable for archival description.
- Include up to 10 **Keywords**, separating each with a comma and using proper capitalization. These keywords should allow the user to quickly learn what topics are discussed in the interview.

#### Signed Release File
Upload a scan PDF copy of the signed [release form](https://csudigitalhumanities.org/about/interviewee-faq/) for the interview. This is required for publication of the interview. Physical release forms should also be provided by mail, but the digital copy is still required.

Give this file a name that includes the numeric identifier, e.g. `XXXXXX release.pdf`. 

## Transcription Guidelines
In most cases, a project administrator will create an AI-generated transcript/caption file on your behalf and upload it for you to proof and correct as needed. These initial transcripts may include significant errors. Below are some basic guidelines for improving upon the generated transcript.

### Readability
Make sure that it is relatively easy to read the interview using the transcript. This does not mean that all grammar should be corrected. When speaking, most people do not use proper grammar or even complete sentences, and many stumble over their words, stutter or repeat themselves, add *ums* and *uhs*, or take long pauses. **In most cases, it is best to leave these idiosyncrasies in place**. The exception would be when transcript accuracy actually impedes readability. 

For example if the uncorrected transcript reads:

```
“The date was I think like well may be yeah it was ok oh man sorry it was January fur Jan you January first twenty um ten January first twenty ten”
``` 

You could probably edit that to be more concise, as in:

```
“The date was, I think, [...] January 1st, 2010”
```

In this example, the phrase “I think” was sufficient to communicate that the speaker had some doubts and the bracketed ellipses `[...]` indicate that some content has been omitted. 

The key considerations when editing for readability are that your changes must never *misrepresent* the speaker, and must not *obscure* meaning, and must not *omit* useful information.

### Punctuation
Make sparing use of advanced punctuation, adding improvements only where it is necessary to reach a baseline of readability. Most of the time it will be fine to end incomplete sentences with a simple period. It is not necessary to put every nested aside between em dashes. It is not necessary to put every spoken quotation in actual quotes. It is not necessary to use commas for every single clause or preamble. As a general rule: when in doubt, maybe just use a period?

Look for instances where the existing punctuation is problematic for reasons of readability or meaning. For example, consider how the placement of a period and a comma affects the meaning of the following statement.

Original transcription:
```
The murderer protested his innocence an hour after he was hanged.
```
Improved transcription:
```
The murderer protested his innocence. An hour after, he was hanged.
```

### Spelling and Capitalization
Spelling is perhaps the most common improvement you will need to make. 

Spelling issues are not always easily identifiable via a quick scan of the transcript (not even with spell check turned on), as its usually the case that a valid (but inaccurate) word has been used in place of what the speaker actually said. In some cases, the transcript will actually include a series of inaccurate replacements that lead to a grammatically-correct sentence. 

Look in particular at the spelling of proper nouns, especially those tied to local places and culture. For example, it’s not uncommon to find Cayuga instead of Cuyahoga. 

Regional and ethnic accents and uncommon terms can also influence transcription accuracy. For example, you might find “pro geese” instead of pierogis or "vans where engine" instead of Van Sweringen.

If you’re unsure how to spell personal names try searching online. Newspaper and obituary results are often most helpful.

Sometimes the words themselves may be correct but are not properly capitalized, spaced, or formatted. For example, look out for “metro parks” when the more accurate transcription would be Metroparks (when speaking of the Cleveland area park system). Likewise, Sherwin-Williams is always hyphenated (when speaking of the paint company) and “Lake View” is always two capitalized words when speaking of the east side cemetery.

### Quotations
Generally, you do not need to place spoken quotations inside quotation marks. The exception would be when the speaker is unambiguously intending to communicate an exact quotation. 

For instance, do use quotation marks for the following:

```
My favorite Ghoulardi catch phrase is "Stay Sick!"
```

Do not use quotations marks for reported speech that may be paraphrased:

```
Ernie Anderson told me don't bother calling the station manager, he doesn't listen anyway.
```

### Sensitive Information
If you encounter a birth date, omit the exact month and date (leaving the year intact if applicable) by using editorial brackets. You can use bracketed ellipses or some other bracketed word or phrase that maintains the cadence of the sentence being edited. For instance, you could use “I was born [...] 1990” or instead “I was born [in] 1990” – either is fine. 

### Crosstalk
It is not uncommon for interview participants to interrupt, interject, or speak over one another in the course of the interview. This could be a simple "wow" spoken by the interviewer as the interviewee is telling a story or it might be a more complicated and substantive back and forth. In some cases, the generated transcript may attribute text to the wrong speaker. In extreme cases, crosstalk makes parts of the audio difficult or even impossible to decipher. Exercise judgment when deciding how to handle crosstalk. 

If the crosstalk cannot be effectively transcribed or if it doesn't convey any useful information, you may simply annotate the passage with `[crosstalk]` to indicate that there was some crosstalk happening in that moment, which may impact accuracy.

If the interviewee repeatedly interjects with affirmations like "ah ok" and "uh huh" you may simply omit those from the transcript.

If crosstalk results in a passage that is incorrectly attributed or not transcribed at all, fix the error, adding the correct speaker names, timestamps, and text. If needed you may reuse a timestamp for consecutive blocks where participants are speaking at the same time. For example:

```
Angelo [00:02:01] And what year was that?

Mia [00:02:04] That was 1967.

José [00:02:04] That was 1969.

Mia [00:02:07] Oh yes José is correct actually. 1969.
```

### Indecipherable Words or Passages
Sometimes a passage may be difficult or impossible to accurately transcribe due to crosstalk, heavy accents, unidentifiable words, or file corruption. If an accurate transcription cannot be ascertained you may add `[inaudible]` to indicate where the issue occurs. Do not use qualitative annotations like "slurred" or "garbled," which may offend the speaker.

### Speaker Names and Timestamps
Make sure that the speaker names are uniform and correct and that the speaker name is always displayed along with the timestamp. Below is an example of the correct format:

```
Jane Doe [00:00:00] Good morning. Today is the 31st of December. I am here at the university library interviewing Father John R. Smith of Saint Vladimir Cathedral. [00:00:10] Please state your name for the record, Father.

John Smith [00:00:15] Father John R. Smith. Happy to be here.

Jane Doe [00:00:18] Ok, let's get started.
```

- Note that the **speaker name** label `John Smith` does not include the honorific or middle initial. 
- Note that the **timestamp** `[00:00:00]` is inside brackets, is formatted as hh:mm:ss, and is surrounded by a single space on either side. 
- Note that there is an **inline timestamp** `[00:00:10]` in the first speaker section. Inline timestamps can generally be deleted, especially when they’re only a few seconds separated from the preceding one, as in this example. In some cases you may leave an inline timestamp in place if the speaker section is very long and a user might find it convenient to jump to an intermediate location. But usually the timestamp should only be included where there is a speaker change.

### Formatting
The transcript file must be in plain text format (no formatting whatsoever is allowed) and must use the `.txt` file extension.

Please include a single blank line between each speaker section.

## FAQ
### How do I make sure I’m using a plain text file format?
The simplest way to ensure that you’re using plain text is to use a code editor such as [Visual Studio Code](https://code.visualstudio.com/) or a markdown editor like [iA Writer](https://ia.net/writer). Getting familiar with professional tools like these is generally a good idea and worth the little bit of adjustment that might be required.

You can also use the built-in [TextEdit](https://support.apple.com/guide/textedit/welcome/mac) app for MacOS or the [Notepad](https://apps.microsoft.com/detail/9msmlrh6lzf3?hl=en-US&gl=US) app for Windows but in both cases you must ensure that you are saving the file in plain text format.

When saving the file, make sure the file extension is `.txt`.

*Do not* use Microsoft Word, Apple Pages, Libre Office, Google Docs, or any other document design software when working with plain text, especially when creating content for the web. These apps are designed around print-based use cases and often add hidden formatting and other junked-up characters that can be disruptive in online contexts. 

### Why do I need to transcribe the interview? 
The transcript provides details that are not easily extracted from an original audio or video file. By providing a text-based transcript, the contents of the interview can be more easily indexed by search engines and more easily discovered by researchers. They also provide a scannable preview of the original audio, making it easier to determine if the contents are relevant to the user. Moreover, transcription produces an equivalent experience for hearing-impaired users and others who may not be able to use the interview in its original form. Making interviews accessible is the right thing to do for project success, for researcher access, and for users, particularly those with sensory disabilities but also those who simply wish to read or scan. It’s also required by state and federal law, as well as by CSU Library, in accordance with the Americans with Disabilities Act (ADA).

### How much time do I need to correct an interview transcript?
If you were present at the recording of the interview, it should not take very long to make the necessary corrections – maybe just the duration of the recording. If you are transcribing an unfamiliar interview it may take longer – perhaps twice the length of the recording or a bit more. In any case, this is much faster than traditional transcription from-scratch which often took non-experts up to 10 times the duration of the recording.

### Why are sponsors listed for some transcribed interviews?
In 2020, in order to raise funds to cover transcription costs, particularly for the large backlog of existing interviews, the Center initiated a [crowdfunding campaign](https://crowdfunding.csuohio.edu/project/18219) to allow individuals and organizations to sponsor interviews by making a tax-deductible donation to the CSU Foundation. 
