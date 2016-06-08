# Single-Sign-On-z-druzabnimi-omrezji

Opis:

V tem projektu so razvite aplikacije, ki s pomočjo odprtokodnih knjižnjic omogočajo enotno spletno avtentikacijo ter prijavo uporabnikov v družabna omrežja Google+, Facebook, Twitter in LinkedIn. Aplikacije imajo uporabniške vmesnike (Java Swing za Javo) in so razvite v jezikih C# (ASP.Net) in Java.

Google+: Za .NET in Javo je uporabljen primer na strani https://developers.google.com/+/web/samples/csharp?hl=bg. Ta primer demonstrira uporabo knjižnjice Google APIs.

Facebook: Uporabljeni sta knjižnjici Facebook.NET SDK za C# in Facebook4j za Javo.

Twitter: Uporabljeni sta knjižnjici TweetSharp za C# in Twitter4j za Javo.

LinkedIn: Uporabljeni sta knjižnjici ASPSnippets.LinkedInAPI za C# in Scribe za Javo.

Vse aplikacije vsebujejo sistem glasovanja za najljubše družabno omrežje. Ta sistem shrani podrobnosti uporabnika in čas glasovanja v datoteko v formatu JSON. Aplikacija dotNet Glasovanje prebere datoteke JSON, prešteje glasove in izpiše podrobnosti za vsak glas posebej. Rezultati se shranjujejo v mapo C:\\Rezultati. Za obdelavo datotek v JSON formatu skrbita knjižnjici Json.NET za C# in JSON.simple za Javo.

EDIT: Zraven so priložene knjižnice, treba pa je uporabiti svoje žetone, vrednosti ter localhost poti, ker so trenutne vrednosti potekle. Ker je projekt že nekoliko star, bo mogoče treba posodobiti obstoječe knjižnjice.
