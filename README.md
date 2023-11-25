# natHacks_2023_boreme

EEG files were too big to upload.
Devpost link containing our presentation: <https://devpost.com/software/brome>

## Inspiration

Dating has never been harder. Although many of us are fixated on finding our “type”, studies have found that it’s actually highly difficult to predict who we’ll be attracted to as a romantic interest. Intrusive thoughts, social pressures and self-perception and the criteria restraints of our “type” can get in the way of feeling sure about a potential partner. Enter BoreMe, where we've decided to put an end to the mystery by diving into the depths of your brain waves. Inspired by the chaos of modern dating, we've harnessed the power of the Muse S to decode the enigma that is your interest level.

## What it does

Not only does BoreMe leverage the Muse S to delve into the depths of your brain activity, but it also incorporates the cutting-edge Adafruit Feather v2 to provide real-time feedback through a colorful light display. Imagine being in the midst of a speed date, exchanging pleasantries and witty banter. Meanwhile, the Adafruit Feather v2 is working its magic, ready to reveal the chemistry between you and your date.

As the conversation unfolds, the BoreMe app interprets your brainwaves, utilizing research that links decreased beta waves and increased alpha and theta waves to boredom, while decreased alpha and theta with increased beta waves imply interest. The Adafruit Feather v2 becomes your silent ally, emitting a vibrant green light when sparks fly and genuine interest is detected. Conversely, if the app senses the subtlest hint of boredom, a telltale red light discreetly appears, signaling that it might be time to switch up the conversation or gracefully exit the speed dating stage.

BoreMe transforms the dating game by merging neuroscience and technology, offering a visual cue that transcends words. Whether navigating the unpredictable terrain of a speed date or enjoying a leisurely chat over coffee, let the Adafruit Feather v2 illuminate the path to romance with colors that speak louder than words. BoreMe isn't just a dating app; it's a visual symphony of connection, making the journey to find love as exciting as the destination.

## How we built it

Hardware Components:

1.) Muse S: The brainwave powerhouse. We integrated Muse S to capture EEG data, providing us with a wealth of information about your neural activity during a date. 2.) Adafruit Feather v2: Our visual storyteller. This nifty device serves as the interface between your brain and the outside world. Using its LED capabilities, it communicates with you in real-time, with a green light for interest and a red light for boredom.

Software Framework:

1.) BrainFlow: The neural maestro. We employed BrainFlow to seamlessly stream and record EEG data from the Muse S. It ensured a smooth flow of information, laying the groundwork for our in-depth analysis. 2.) Scikit-learn: The brain translator. This powerful machine learning library became the backbone of BoreMe. We trained our algorithms to understand the intricate patterns within the EEG data, distinguishing between moments of genuine interest and the subtle pings of boredom. 3.) FFT (Fast Fourier Transform): The preprocessing virtuoso. To make sense of the raw EEG data, we used FFT to transform it into frequency-domain information. This step was crucial in extracting meaningful features that our machine learning models could analyze.

Challenges we ran into

Developing BoreMe posed several challenges, including training a nuanced machine learning model to interpret EEG data for genuine interest versus boredom. Crafting a unique concept in the crowded dating app space required inventive thinking. Translating the idea into a tangible product involved overcoming hurdles in 3D printing for a sleek, functional prototype. Integrating hardware, like the Muse S and Adafruit Feather v2, with a sophisticated software framework demanded meticulous coordination. Despite these challenges, the BoreMe team embraced innovation, transforming obstacles into opportunities and delivering a dating app that reads minds, reflecting the resilience behind its creation.

## Accomplishments that we're proud of

Our journey with BoreMe has been a rollercoaster of accomplishments, and we're beaming with pride at what we've achieved. Transforming the initially humorous concept of reading romantic interest through brainwaves into a tangible reality is an achievement in itself. We successfully trained a sophisticated machine learning model to decode EEG data, navigating the complexities of distinguishing genuine interest from boredom.

Crafting a unique and functional prototype through 3D printing showcased our ability to turn imaginative ideas into a tangible, user-friendly product. BoreMe isn't just a funny idea anymore; it's a testament to our team's creativity, resilience, and commitment to bringing innovation to the world of dating.

## What we learned

Embarking on the BoreMe project was a profound learning experience for our team. In delving into neurotechnology and techniques, we expanded our collective knowledge, gaining insights into the intricate world of brainwave analysis. The journey taught us the value of patience, especially when training a machine learning model to decipher subtle neural signals. Resilience became our ally as we tackled challenges in hardware integration and prototype development, turning setbacks into stepping stones. Teamwork emerged as the linchpin of our success, as each member's unique expertise contributed to the realization of BoreMe. Ultimately, we learned that innovation thrives on collaboration, adaptability, and a shared commitment to pushing boundaries.

## What's next for BoreMe

The future for BoreMe holds exciting possibilities. Our immediate focus is on developing a fully functional app, seamlessly integrating the brainwave analysis capabilities of Muse S with real-time feedback from the Adafruit Feather v2. Taking it a step further, we plan to expand our bio-signal repertoire to include ECG, skin temperature, and skin conductance, providing a more comprehensive understanding of user engagement.

Collaborations with dating app companies are on the horizon, as we aim to bring BoreMe's unique insights to a broader audience. By harnessing a combination of neurotechnology and physiological signals, we envision a future where BoreMe becomes an indispensable tool in deciphering and enhancing romantic connections. Stay tuned for a revolutionary approach to dating that goes beyond words and into the realm of bio-signals.

