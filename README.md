# typescript-exercisos
```typescript
/**
 * Consider a const like so
 */const stuffo = {
  A: {
    a1: "a1",
    a2: "a2",
    shared: "shared",
  },
  B: {
    b1: "b1",
    b2: "b2",
    shared: "also shared",
  },
} as const;

/**
 * The aim is to make a type T which is the union of all possible leaves, i.e.
 * "a1" | "a2" | "shared" | "b1" | "b2" | "also shared"
 */
 
 /**
 * The previous exercise was made a lot simpler by virtue of the leaves all being at the same
 * level, try now to do the same in the more generic context where the object looks like
 */
 
 const stuffoharder = {
  A: {
    a1: "a1",
    a2: "a2",
    shared: "shared",
  },
  B: {
    b1: "b1",
    b2: "b2",
    shared: "also shared",
    nestedbois: {
      thingyeah: "hiya",
    },
  },
} as const;
/**
 * Write a type NotBoth<S, T> such that an element of type NotBoth<S, T> can be of type S and can be
 * of type T, but can not be of type S & T
 */
 
 /**
 * Try to make sense of this JSON parser at type level written in typescript
 *
 * https://www.typescriptlang.org/play?ts=4.1.0-pr-40336-88#code/C4TwDgpgBACghgJwM4QQUQQg9ggPAFSggA9gIA7AEySiWAQEtyBzAPigF4oBvIzHAFxR6AV2gBfKADIo+AFChIUNHGAB1ABYMySMHADGEXAGVgq6CTJUadRi3Yc5UWvSbMipCtSinzT51AA-LCIKOj8eABEKupaOnqGUMxYwEkUqAz6LnbuihCRrP7OQr5kHlbeAAZQACTcTABmqD5mZOLVAD5QlQA65HWNzaUQ7UUBwTGa2hC6BkbDhQEBJa0QCuDQAIKUlADSECAAanAANmK4ALIQALZY5V40AEoQ+jiUuLZuADRQcOQgrB++xA92s2W+UGOZwsnjBfwBnCg-iut2kPCgAG1dlAmFBgQBdIRQsRQcTrJTwZAQABSSCw5AA8gAjABWL2AJlWoO8nxYPxRd0sDygz1eCHevOYP3hDh44gc-kl3JowzGwUpYQw2CiGppdMZrPZSRSaXIGSySryBTGQkmcRmCXmq3YQrBlXEA3ITQQLXMoyWzmCGIFP2G+LGxWUqim8TmnPMLthVUinu9eIO4hT9S9Q1W-oDgajsWms0M8bIiYqNEqAlTub9lQjAfVoT19OJToTysxgx9HZ+lTrPuG7XDBYLE2j9tLnYr3cqXyHvrajfH45bVNp9OZbP0HOGP22ewOHcuNywQIOPw7rEWa4DtqnJcd5YgleF7qXI9X94nmKPwKniG6YgNepxiICy4QGOv4PiEVLhNquCVLqW4GruqQIC8EAMAAbhAlBQCIZrEJAe4EcIWAANYUEIdTfnev5CLqiE4MhqH6h2UBYcAIgIGahHESQZFkIRuHgdADSCLU3AMU2SzMa2rF4ChrZoTuRpYYYeEUUJpHshRwDUbRMlyWuikIVqbGqZu+oaXu3HYTpgkkSJhnGeQdGyXmlSFHk8EoGhmyYHAICvt2kr8ue3bwhi+KInFCrOEqrreKqSwbpqES4JEHH0sFCChcaqTMOkjAWq4LDCBs1oKUWMYOnGCzzviX4+U2QbAWGTYWYFnESa+75ghivaQhJA5tQ2MF-naz5Nc686LtmabfvJ4wBW25AFaFuCzbGZYLD8GIAHSncBHb4ox46PsW+2zm+LWTSua0ZZiJ1neeYHQvioarNN969agVkqXlW0hSCWk4fhLnCQZhFGTRnmmT5V11SxwPsWp-XQo5vH8bprlw1A4k41JCBeXJ-mg6ewwRZVbCcIq9Pdul63o9luVY+2EnFaa5rglVVpXTdDUzoN87kCIJwnE9Iw-q9GKS9Lv3mP9kZ7Y1B0Lal1ZZqNHaZrL+Z-hi-ZQWryz1dOL7NTr3QYkb8vrhtQXg4NL1QCL1vzV2duVNwjse4WoP2fuzpB57G3KZjtnczjkPOURhPkfDHkUyj5LQKDBB0zkSUu9j5z4EN3ijc8SBS8AaoijMlfdiNOZ9uNAvMBbwQdj1NcVycqR2+zSEymtwTl5Xa2A9HnOx+QXE8XxAlJ7DKdd5XtWW-3bGT31cckrP+Mub2hVMic0Ajz3BQANxyFf1+Z1AaGItnADkvCRDRIAAIyREIGKRCTYifz8JWJwfpQFfgcAATF-UBf8ICQNJI-Vgl8b7XyAA
 */```
