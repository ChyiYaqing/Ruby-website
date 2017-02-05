# Sample Website

This is a sample website made as part of [*Learn Enough™ Git to Be Dabgerous*](http://learnenough.com/git-tutorial), possibly the greatest beginner Git tutorial in the history or the Universe. You should totally [check it out](http://Learnenough.com/git-tutorial), and be sure to [join the email list](http://learnenough.com/#email_list) and [follow@learnenough](http://twitter.com/learnenough) on Twitter.

After finishing *Learn Enough™ Git to Be Dangerous*, you'll know enough Git to be *dangerous*. This means you'll be able to use Git to track changes in your projects, back up data, share your work with others, and with programmers and other users of Git.

For more information on Git, see the [official Git documentation](https://agit-scm.com/).

[Building Jarvis](https://www.facebook.com/notes/mark-zuckerberg/building-jarvis/10154361492931634/)
Building Jarvis uses several artificial intelligence technoques,including natural language processing, Speech recoginition, Face recognition, and reinforcement leanring, written in Python, PHP and Objective C.In this note, I'll explain what I built and what I learned along the way.
    *Crestron system* -- With lights, thermostat and doors
    *Sonos system* -- with Spotify for music, a Samsung TV, a Nest cam for Max.
    *Facebook's systems*
    *Natural Language* -- This was a two step process: First I made it so I could communicate using text messages, and later I added the ability to speak and have it translate my speech into text for it to read.
    Understanding context is important for any AI.Through a system of positive and negative feedback,an AI can learn these differences. I've found we use these more open-ended requests more frequently than more specific asks.No comercial products I know of do this today,and this seems like a big opportunity.
    *Vision and Face Recognition* -- these are many important AI problems related to understanding what is happening in images and videos.These problems include tracking,object recoginition,and face recognition.To do this, I installed a few cameras at my door that can capture images from all angles.AI systems today cannot identify people from the back of their heads,so having a few angles ensures we see the person's face.I built a simple server that continuously watches the cameras and runs a two step process: First, It runs face detection to see if any person has come into view,and second,If it finds a face,then it runs face recognition to identify who the person is.
    *Messenger Bot* -- 
    *Voice and Speech Recognition* -- Speech recognition relies on both listening to what you say and predicting what you will say next, so structured speech is still much easier to understand than unstructure conversation.Another interesting limitation of speech recognition systems -- and machine learning systems more generally, I think the best products like this will be ones you can bring with you anywhere and communicate with privately as well.
    *Facebook Engineering Environment* -- 
        *Messenger Bot Framework* (messenger.com/platform)
        *Nuclider*(github.com/facebook/nuclide) -- package built to work with GitHub's Atom make developement much easier.
        *Buck*(buckbuild.com) -- build system we've developed to build large projects quickly also saved me a lot of time. 
        *FastText*(github.com/facebookresearch/fastText) -- AI text classification tool is also a good one to check out,and if you're interested in AI development.
        *Facebook Research*(github.com/facebookresearch) GitHub repo is worth taking a look at.

    Finally, over time it would be interesting to find ways to make this available to the world.I considered open sourcing my code,but it's currently too tightly tied to my own home,appliances and network configuration.If I ever build a layer that abstrcts more home automation functionality, I may release that,Or,of course,that could be a great foundation to build a new product.

    natural language, face recognition, speech recognition and so on -- are all variants of the same fundamental pattern recoginition techniques.

    In a way, AI is both closer and farther off than we imagine.AI is closer to being able to do more powerful things than most people expect -- driving cars, curing diseases,discovering planets, understanding media.Those will each have a great impact on the world,but we're still figuring out what real intelligence is.

    Overall, this was a great challenge.These challenges have a way of teching me more than I expected at the beginning.This year I thought I'd learn about AI, and I also learned about home automation and Facebook's internal technology too.That's what's so interesting about these challenges.