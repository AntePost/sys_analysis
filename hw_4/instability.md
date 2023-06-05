Формула instability: `Ceff / (Ceff + Caff)`

На основе [схемы](/hw_0/schema.drawio.png) из нулевой домашки instability сервисов имеет следующие значения (связи с frontend не учитываются за исключением Test service, где с frontend идут данные о новых кандидатах):
- Client service: `1 / (1 + 1) = 0.5`
- Orders service: `6 / (6 + 3) = 0.(6)`
- Paraphernalia service: `1 / (1 + 1) = 0.5`
- Quality control service: `0 / (0 + 1) = 0`
- Worker service: `1 / (1 + 1) = 0.5`
- Bets service: `1 / (1 + 1) = 0.5`
- Client billing service: `1 / (1 + 1) = 0.5`
- Worker billing service: `1 / (1 + 1) = 0.5`
- Test service = `1 / (1 + 1) = 0.5`

На удивление хорошие показатели, хотя у orders несколько высокий и надо учитывать, что я не выносил matching из orders.
