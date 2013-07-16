sweet task markup language
=================

(I) Here's a way to document all the sweet stuff you want to do in life, using text, and in time a bin directory (T)(Q).

	Legend ------------------------------
	
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
	
		--- scraping patterns -----
			[^\s].+\([BCDFIMNPQRTZ]+\).+$ = All tagged notes
			[^\s].+\([0-9]{1,2}\.[0-9]{1,2}\).+$ = Development process tasks
			[\s]+->\s.+$ = Current Tasks
			
	Example high priority task list ------------------------------
		
		-> Doing that thing I was planning to do
		>- Then after I'll do this
		>- Then after after I'll do that
		-- And some other time I'll do this
		./ But it may be a while until I get to this
		(R) As long as I actually get to it, (C) it's okay.
		
