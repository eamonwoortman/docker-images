# ReportUnit

ReportUnit image which can be used to generate an HTML report from an NUnit XML report using [RelevantCode's ReportUnit](http://relevantcodes.com/reportunit/). 


Usage
-----

To use the image, bind a folder containing your output XML and run the container with the input path(ie. where the NUnit XML is located) as parameter and optionally an output folder.


	docker run -v /home/eamon/nunit-output/:/input \  
				eamonwoortman/reportunit-docker \
				"/input"

or 
	
	docker run -v /home/eamon/nunitoutput/:/input \ 
				eamonwoortman/reportunit-docker \
				"/input" 
				"/home/eamon/nunit-report"


