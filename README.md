# NLPCALLSCHEDULER
This repository contains the source code for an NLP service aimed at improving end user productivity. The service focuses on scheduling Microsoft Teams calls based on user input statements. The service takes statements like "Schedule a call with Sriram and Divya at 4:30pm" or "Schedule a call with sriram, divya, and chidu" and schedules a call with the specified participants while considering everyone's timezone, working hours, and their availability.

The NLP service incorporates several features to facilitate efficient scheduling. If the user does not specify a time, the service automatically schedules the call at the earliest available slot. To accurately identify participants, the service utilizes a recently contacted list from Microsoft Teams. This enables the service to estimate the intended recipient even if only a partial name is provided.

Additionally, the service provides auto-suggestions while the user is typing the names of meeting recipients, ensuring convenience and accuracy. It also offers auto-suggestions of names from the entire list of organization members, further enhancing the user experience.

The service integrates with the scheduling assistant in Microsoft Outlook to determine the availability of common time slots for all participants. If the requested time slot is available, the service schedules the Microsoft Teams call and returns the meeting details with the message "Call successfully scheduled at the requested time." However, if the requested time slot is unavailable, the service provides the top three earliest available slots as alternative options.

This GitHub repository includes the source code and documentation necessary for understanding and implementing the NLP service within a digital assistant application. It also includes instructions for integrating with Microsoft Teams and Outlook, enabling seamless scheduling of calls while optimizing end user productivity.



