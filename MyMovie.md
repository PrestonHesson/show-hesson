# Preston Hesson

## My Favorite Movie: The Princess Bride

One of my all-time favorite movies is **The Princess Bride**. I love this film because of its **perfect blend of adventure, romance, and humor**. The movie has unforgettable quotes, a fantastic cast, and a timeless story filled with sword fights, witty dialogue, and true love. Cary Elwes' performance as Westley, along with the film’s charm and humor, makes it an all-time classic that I can watch over and over again.

![Cary Elwes as Westley](cary_elwes.jpg)

---

## Alternative Actors for the Main Role

If Cary Elwes had not played Westley in *The Princess Bride*, there are several other actors who could have brought a unique charm to the role. Below is a table of four actors I think would have been great choices for the part.

| Actor Name      | Reason for Choice                                  | Age |
|-----------------|----------------------------------------------------|-----|
| Tom Hiddleston  | Has the wit and elegance needed for the role       | 42  |
| Errol Flynn     | Classic swashbuckler with legendary sword skills   | N/A (Deceased) |
| Emma Stone      | Would bring a fresh, witty, and fun new take       | 35  |
| Heath Ledger    | Had charisma and charm perfect for the character   | N/A (Deceased) |

---

## Inspirational Quotes

Here are two inspirational statements from well-known figures that I find meaningful:

> "Do what you can, with what you have, where you are."  
> *—Theodore Roosevelt*

> "Success is not final, failure is not fatal: it is the courage to continue that counts."  
> *—Winston Churchill*

---

## Code Snippet

Below is a useful TypeScript snippet that demonstrates a **debounce function**. This function delays invoking a provided function until at least the specified number of milliseconds have elapsed. It is useful for optimizing performance in scenarios like search input handling or event listeners.

```typescript
const debounce = (fn: Function, ms = 300) => {
	let timeoutId: ReturnType<typeof setTimeout>;
	return function (this: any, ...args: any[]) {
		clearTimeout(timeoutId);
		timeoutId = setTimeout(() => fn.apply(this, args), ms);
	};
};
https://code.pieces.app/collections/typescript