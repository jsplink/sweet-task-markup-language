sweet task format
=================

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
	
		--- time estimations -----
			{<est>,<act>} = Estimate, actual. In hours.
	
		--- sub tags -----
			($) = Money Out
			($$) = Money In
	
		-- scraping patterns -----
			[^\s].+\([BCFIMNPQRT]+\).+$ = All tagged notes
			[^\s].+\([0-9]{1,2}\.[0-9]{1,2}\).+$ = Development process tasks
			[\s]+->\s.+$ = Current Tasks
