# Everything is Better With Pizza Book Club 🍕📚

## Logo

![Logo](assets/images/logo.png)

## Bugs
1. Homepage keeps with an extra margin on the right side.

    I had a margin of 2rem on the about-us section that was causing the issue. I commented section by section to see which one was causing the issue. I added a 0 on the margin for the sides.
2. Footer was not sticking to the bottom.
    I put bottom: 0, but it still was not working. Devtools showed that it would not be changed with a static position. So I changed the footer position to absolute and width to 100% because it change the width to smaller when I changed the position.
    Changing to absolute worked with pages with less content but not with larger content, so I changed to fixed and it worked.
    Fixed did not work with larger contents. I changed the body to min-height: 100vh; display: flex; flex-direction: column; and added flex-grow: 1 to the join-us section which was the only one that the content did not reach the end for the footer to stay in the bottom as suggested here https://stackoverflow.com/questions/34796085/how-to-stick-footer-to-bottom-not-fixed-even-with-scrolling
    
    

## Books' Images
- January: https://www.amazon.co.uk/N%C3%B6thin-But-Good-Time-Uncensored/dp/1250195756
- February: https://www.amazon.com/Fire-Blood-Thrones-Targaryen-History-ebook/dp/B07C6TBTV3
- March: https://www.kobo.com/ie/en/ebook/friends-lovers-and-the-big-terrible-thing-2
- April: https://www.amazon.ca/Find-Your-Why-Practical-Discovering/dp/0143111728
- May: https://www.amazon.co.uk/Storyteller-Tales-Life-Music/dp/139850372X
- June: https://www.amazon.co.uk/AM-Club-Your-Morning-Elevate/dp/1443456624
- July: https://www.amazon.co.uk/First-21-York-Times-Bestseller/dp/1408716119
- August: https://www.amazon.co.uk/Beautiful-World-Where-Are-internationally/dp/0571365426
- September: https://www.amazon.com/Beyond-Wand-Mayhem-Growing-Wizard-ebook/dp/B09ZXMG884
- October: https://www.easons.com/the-midnight-library-matt-haig-9781786892737
- November: https://www.amazon.co.uk/Madly-Deeply-Alan-Rickman-Diaries/dp/1838854797
- December: https://www.goodreads.com/book/show/57425158-the-opposite-of-butterfly-hunting

## Help
- Add the hand to the cursor on the buy button: https://developer.mozilla.org/en-US/docs/Web/CSS/cursor
