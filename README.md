Ai Planned Trips
Project Link: https://srishanth-kargaom.github.io/Srishanth-Kargaom-apt/
It is an event-based optimized trip plan generator. It helps users find the most suitable trip plan from the generated options, saving time
when traveling to unfamiliar cities or planning visits to various destinations. The platform is designed to accommodate all economic
standards by offering customizable filters.
Currently, only the front-end part made publicly available on GitHub.

APT Railway (a subsidary of Ai Planned Trips)
Project Link: https://srishanth-kargaom.github.io/Srishanth-Kargaom-apt/railway.html
This project is part of the larger initiative, APT (Ai Planned Trips). APT_Railway is one of the key features of the APT project, designed
to optimise railway ticketing. Work on the APT project is progressing steadily toward its release.
#some details about Guaranteed Seat Assistance:
In Indian Railways, if a ticket is unavailable between your boarding and destination stations for a train, you have two alternative
methods to book your ticket, since the availability of tickets depends on boarding and destination points:
Type-1: It generates a list of all possible routes with extended boarding and destination stations in ascending order of distance, where
you can check availability.
Type-2: It offers a breakdown version where you may need to book two or more tickets to secure confirmed tickets. It generates all
possible routes with extended boarding and destination stations, including intermediate stations, in ascending order of distance.
Website Features and Benefits
This website currently uses the type-1 algorithm to help users book confirmed train tickets at optimal costs. It surpasses existing third-
party ticketing solutions in efficiency, cost-effectiveness, and reliability. This website is limited to train 20804, as this algorithm uses
distances between each station and lack of IRCTC's API access.
Note: It is limited to train 20804 which used as a sample due lack of access to realtime irctc api's.It only geerates the list of possible
outcomes according to optimal cost and it doesnt verify the availability of tickets with irctc servers.The user needs to check the
availability by help by apt-railway
Premium Tatkal Assistance:
APT_Railway also aids users in Premium Tatkal booking:
Premium Tatkal is available only between selected station pairs.
Normal Tatkal users often miss out on confirmed tickets due to delays in manual booking (1+ minute), whereas counter bookings
happen within 20–30 seconds.
Railway counters do not book Premium Tatkal, so opting for it online gives you an edge.
Note on Premium Tatkal:
• The system generates a sorted list of optimal boarding and destination combinations, including those eligible for Premium Tatkal,
ranked by cost efficiency.
• Important: APT_Railway does not check real-time ticket availability for Premium Tatkal tickets. Users must verify actual ticket status on
the official IRCTC website or authorized platforms before proceeding with booking.
• Premium Tatkal bookings are typically limited to specific station pairs and are priced higher than normal Tatkal tickets. Since railway
counters do not handle Premium Tatkal, online bookings can be highly competitive and often take longer (more than a minute), whereas
counter bookings for normal Tatkal tickets occur much faster (within 20-30 seconds).
• By suggesting the most cost-effective station pairs(boarding and destination) for Premium Tatkal, APT_Railway improves users’
chances of securing a seat by guiding them where to book manually.
