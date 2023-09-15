This is a large and rambling website concerned with the historical record of my grandparents, great-grandparents and their families and other contemporary relations.

Boring to anyone not a relative.  But I learned a lot about CSS when I upgraded it from the original 1252 standard to the present UTF-8, always attempting to preserve the appearance.

UTF-8 incorporates the extensive use of Cascading Style Sheets (CSS), obviously a powerful tool.  My problem was that the earlier 1252 standard had some "goodies" that UTF-8 seems to lack.  Or is that simply due to my own limitations with CSS ?

Therefore, in some instances I felt compelled to incorporate bits of 1252, despite objections from my HTML/CSS Validator program.  I will need to re-visit this website to incorporate improvements when my knowledge of CSS expands.  Here follows a list of some of the difficulties I encountered:

(1).  How to maintain continuous audio when the user clicks on hyperlinks.  To do this I have made use of "frames" (which are now obsolete).  One frame has a width of 0%, the other has a width of 100%.  The 0% frame contains the audio code and goes no further.  The 100% frame leads to all the remainder of the code.  Perhaps Javascript is the answer?

(2).  When a new page is selected (by a hyperlink) I do not always wish the new page to start at the top.  Depending upon the context, I might wish the new page to display itself somewhere in its middle.  With 1252 this is easily done by using:  <a name="my_label"></a>
But the Validator objects to "name" by branding it "obsolete".

(3).  I like to use "float" where appropriate because it looks stylish.  Float works well in 1252 where it is applied to specific images.  But using CSS, "float" is set-up within the <head> where it gets applied throughout the entire page.  So if the page contains other images that should be non-float then special measures need to be taken.  This involves the use of tables to apply the necessary force.  Yes it can be done, but it's irritating because UTF-8 should be easier to use, not harder.  I have tried incorporating "float" within the <span> keyword, but I can't make that work.

(4).  I find the "no-break" <nobr> instruction (in the middle of text) sometimes very useful.  But UTF-8 doesn't like it.  Why not?  This is a simple and inoffensive instruction.  The objection by UTF-8 might suggest an over-officious attitude by its creators.
