The Q&A plugin is licensed under a GNU GPL2 license as noted in this post by Linc http://vanillaforums.org/discussion/comment/208796#Comment_208796

It is provided here by David Matson to save you time downloading and changing its code to provide the big 'Ask a Question' button.

Check for updates and ask questions about this plugin on its authors page: http://vanillaforums.org/addon/734/q-a

*About the Changes*

I only made code changes specified by peregrine as "The Big Button option part A" spelled out here: http://vanillaforums.org/discussion/26902/some-adjustments-to-more-clearly-see-ask-a-question-in-q-a-1-2-1-new-discussion-button

Compare original and remixed here: https://github.com/HelpGiveThanks/addons/compare/vanilla:2.1...2.1

In addition to these code changes, peregrine also writes that you'll need to add these lines to your config.php file:

$Configuration['Plugins']['QnA']['UseBigButtons'] = TRUE;

$Configuration['Modules']['Vanilla']['Panel'] = array('MeModule', 'UserBoxModule', 'GuestModule', 'NewDiscussionModule', 'NewQuestionModule','DiscussionFilterModule', 'SignedInModule', 'Ads');