a
Easy to create presentation with pydown
python, pydown
Sometimes I don't want waste my time to make presentation which is not so important. At the first stage, I want to focus on the contents, do not care about font'size, font style etc.

Today I checked out [pydown](http://github.com/isnowfy/pwdown)

    pip install python-pydown

and then edit slide.md.

    !SLIDE
    # Hello
    !SLIDE
    # Another slide
    !SLIDE left
    # left
   
lastly, generate it. That's all.

    pydwon slide.md slides