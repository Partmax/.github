# Partmax

Partmax is a marketplace for connecting Mechanics to Independent Partstores and their suppliers. 

Mechanics can now save valuable time with Partmax. Instead of spending 10-20 minutes calling various parts stores, they simply log in to Partmax. In just a few seconds, they can view available stock across multiple stores and efficiently place their order.

## Software Architecture

The Partmax Marketplace is NextJS Web Application running on AWS infrastructure talking to a Postgres DB, with a Redis DB for caching workers. 

There's also an Deliveries Native App written in the Flutter framework which uses the Dart programming language. The Deliveries App allows the drivers to mark the goods as delivered to the Mechanics along with photo proof.

The catalog of parts is sourced from AutoInfo who are the leading industry catalog for parts to vehicles.

Mechanics are provided with a line of credit via Spenda who also provide the payment gateway. Mechanic can also pay by credit card instead of a lines of credit.


## Documentation
* Partmax Marketplace - [https://github.com/Partmax/monorepo]
* Partmax Infrastructure - [https://github.com/Partmax/infrastructure]
* Partmax Deliveries App - [https://github.com/Partmax/deliveries]
* Spenda - [https://dev.sandbox.spenda.co]
* AutoInfo - [http://test.autoinfo.com.au/API/AutoInfoGateway.asmx]



<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

