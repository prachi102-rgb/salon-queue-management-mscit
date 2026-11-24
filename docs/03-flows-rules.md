# Flows & Rules

## Remote customer
1. Home → Join Queue.
2. Enter name and phone, select up to three services and a barber.
3. Confirm creates the next token and opens My Status.
4. Reception calls an eligible customer; status becomes Called and assigned barber is shown.
5. Barber starts service (In chair), then marks Done.

## Walk-in
Reception → Add walk-in → enter name, phone, service and barber → add to end of queue.

## Statuses
Waiting → Called → In chair → Done. Waiting may become Cancelled. Called may become No-show. Completed/cancelled/no-show tokens are not active.

## Queue rules
- First come, first served among customers eligible for the selected barber.
- Call next for barber X selects the earliest Waiting customer who chose X or Any barber.
- A customer who selected a named barber is not assigned to another barber.
- A barber can have one active customer at a time.
- One active queue spot per phone number.
- No-show customers can be re-added as a new entry at the end.
- Online joining can be closed by the owner; reception can still add walk-ins.
- Waiting estimate is the service minutes ahead divided by the number of on-duty, non-break barbers, rounded up. It is an estimate.

## Test checklist
- [ ] Join with valid phone and one service.
- [ ] Invalid phone number is rejected.
- [ ] More than three services cannot be selected.
- [ ] Existing active phone cannot create a duplicate spot.
- [ ] Token is generated and status page opens.
- [ ] Call next skips customers assigned to a different barber.
- [ ] Start changes customer status to In chair.
- [ ] Done removes customer from active queue.
- [ ] No-show and Cancel update the queue.
- [ ] Closing online queue prevents customer joining.
- [ ] Service can be disabled from customer selection.
- [ ] Language toggle changes key interface labels.
