app: scripts that are app-specific (to extract and insert translations)
chatbot: scripts that are RapidPro-specific (to extract and insert translations)
common_tools: scripts to handle (duplicates, best matches, etc.) json files/translation files in a format that is shared between app and chatbot. The current json format (compatible with Translators Without Borders system) is:

{
    "SourceText": "English text, uniquely identifies the bit",
    "text": "Translation",
    "type": "Type of string to translate*",
    "note": "Note for translators"
  }

*needed for inserting the translation back into the system?
For RapidPro the possible types are:text, quick_replies, arguments
For the app the possible types are: ???