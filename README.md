sweet task markup language
=================

Hello world! Here's a way to document stuff you have to do in life, using text. Can't wait until I whip up some bin files!

	Legend -------------------------------------------------
	
	  	--- task list -----
			!- = high priority
			-> = active
			>- = pending another task's completion
			-- = todo
			*- = completed
			.- = deferred
			\- = invalid
			?- = testing required
	
		--- tags -----
			(B) = Blog idea
			(C) = Concept
			(D) = Delegate
			(F) = Feature idea
			(I) = General idea
			(M) = Marketing
			(N) = Note (or FYI, or FMI, rather)
			(P) = Partnership idea
			(Q) = Question / Uncertainty
			(R) = Rule or principal
			(T) = Task
			(Z) = Zzing (Q)
			
		--- development process identification -----
			(1.0) = What development process # this task is in
			(13.37) = ^!^
	
		--- time estimations -----
			{<est>,<act>} = Estimate, actual. In hours.
	
		--- sub tags -----
			($) = Money Out
			($$) = Money In
	
		-- scraping patterns -----
			[^\s].+\([BCDFIMNPQRTZ]+\).+$ = All tagged notes
			[^\s].+\([0-9]{1,2}\.[0-9]{1,2}\).+$ = Development process tasks
			[\s]+->\s.+$ = Current Tasks
