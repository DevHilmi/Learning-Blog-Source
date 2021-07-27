# Transforming Pull Request Format at DANA Indonesia

*Pull Request Review is a good thing to have on every software engineering company, it helps improving team knowledge and prevent bad code from going into the main code base of a project.*

*by Hilmi Ilyas Rizaldi — Software Engineer Android*

// TODO Image

Many developers think that the important thing about pull request review is by seeing the code to review. It’s true, but we need more context to it. How do we know what is the author intention? How do we know what is it for and the effect on software business process? And how can the reviewer understands the context of the pull requests? Well, we need a description of course!

Here is an example of what we did before:

// TODO Image

**That’s right!** It just copying commit messages. It states something that is already stated on Pull request page and not really helping the reviewer.

Description on pull request should describe what is the author intention with the piece of code requested to be merged. Most developers make it very simple and didn’t describe the intentions (e.g: only putting commit messages or nothing at all!) It’s alright if you only code for a small company where everything can be confirmed fast. But what if you are working with a team of hundred developers and all of them use their own style on making a description?

Well, it will be a lot harder to review of course!

Using simple format from that example will create steps like this :

1. Open Pull Request
2. Understanding PR Description
3. See the codes
4. Run the codes (**mandatory** to make sure the code works)
5. **Review the codes**

But if we have a template to follow, it can skip the part of

**“Understanding PR Description”**

. And if the template format is good enough, we can skip some steps and go right into the objective of the pull request,

**to review the codes!**

So what do you need to consider when making the Pull Request template?

# **1. The intention of the code**

The intention of the pull request must be clear, is it fixing something? Improve something? What to improve? What to fix? At least each pull request must have one reason to do so.

# **2. The changes**

The reviewer needs to know what are the code changes. By knowing that part before reviewing, the reviewer will know the part that needs to be focussed on and prevent out of context comment.

# **3. The notes**

Note for the reviewer, of course, let say you change something and need to give reason so the reviewer won’t ask you twice when reviewing. Some example is like this :

- “I’m changing this because it follows the best practice guidelines”

# **4. The Result**

Well, this one is a must. As a developer, how do we know that the project runs as expected if we didn’t test it? Or you can run the project and attach the result, that way you are helping the reviewer to skip this step and immediately

**review the code!**

By taking those four considerations into account, this is how we do our Pull Request in DANA Engineering team:

1. **PURPOSES**: *Explain the purpose(s) of the pull request, can be based on user stories or technical considerations*
2. **CHANGES**: *Explain in short what changes being carried on the pull request*
3. **PR NOTES**: *Explain what the reviewer should notice about the pull request, can be a room for improvement, asking for better practice or even tell the reviewer if the pull request has any dependency to other pull requests*
4. **TEST RESULT**: *Attach test results based on the user acceptance tests (if any)*

// TODO Image

// TODO Image

And there you go, we just created a simple format pull request to be used by your team and saving the time to confirm something on the pull request review process.

Disclaimer: this format is not the absolute best practice, there is always something to improve. Please leave your comments or suggestions. It would be really helpful, thank you.
