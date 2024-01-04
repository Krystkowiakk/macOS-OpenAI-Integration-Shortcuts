# macOS-OpenAI-Integration-Shortcuts

Embrace the future of productivity with macOS shortcuts powered by OpenAI's GPT. Seamlessly integrate advanced text manipulation and translation capabilities into your daily workflow. Perfect as a foundation for crafting your personalized suite of shortcuts, these tools are your gateway to a more efficient, AI-enhanced macOS experience.

## How It Works

The macOS shortcuts work as a conduit between your local environment and OpenAI's powerful GPT models. Here's a step-by-step explanation of the process:

**Highlight or Copy Text**: Begin by selecting the text you want to process or simply copy it to your clipboard.
**Activate the Shortcut**: Use a predefined keyboard shortcut to activate the corresponding macOS shortcut. This action sends the selected text to the OpenAI GPT API, without interrupting your workflow.
**Processing by OpenAI**: The text is processed by the OpenAI API using the GPT model of your choice. In that case OpenAI ensures that your data is not used for training purposes (not like in Chat GPT), maintaining your privacy.
**Receive the Outcome**: The processed text is then sent back and automatically placed on your clipboard.
C**ontinue Seamlessly**: You can instantly paste the outcome wherever needed, allowing you to continue your work without losing focus.
By minimizing disruptions and automating text-based tasks, these shortcuts help you maintain a streamlined workflow, bringing the power of large language models to your fingertips.

## Getting Started

### Prerequisites

Before using these shortcuts, apply for access to the OpenAI API at [OpenAI API website](https://openai.com/api/).

### Configuration

After obtaining your API key:

1. Import each shortcut from the /Shortcuts directory into the macOS 'Shortcuts' app.
2. Enter your OpenAI API Key into the `GPT API Connector` shortcut's text field.
3. For a visual guide on how to assign keyboard shortcuts to these macOS shortcuts, see the following: [Assigning Keyboard Shortcuts](/Screenshots/assigning%20keyboard%20shortcut.png).

## Shortcuts Overview

- **GPT API Connector**: Essential for setting up the connection to the OpenAI API.
- **GPT - Correction Text**: Corrects highlighted text on your screen.
- **GPT - Answer Text**: Provides answers based on the context of a question in your clipboard and your highlighted sketch of the answer.
- **GPT - Translate Menu**: Translates highlighted text into a selected language.

## Usage

To use a shortcut, highlight text or copy it to your clipboard (depending on the shortcut), then run the shortcut using assigned keyboard shortcut. After a couple of seconds, the result will be ready to paste from your clipboard.

## Thanks

Special thanks to Adam Gospodarczyk (@overment) and the AIDevs.pl team for their pioneering work with Generative AI and automations, which inspired the creation of these shortcuts and have made my life better every day.