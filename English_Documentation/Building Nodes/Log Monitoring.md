
tail -F ~/java-tron/logs/tron.log | grep block

tail -F ~/java-tron/logs/tron.log | grep peer

tail -F ~/java-tron/logs/tron.log | grep solid

tail -F ~/java-tron/logs/tron.log | grep -A5 -B2 "MyHeadBlockNum"

tail -F ~/java-tron/logs/tron.log | grep -A2 -B2 "Try Produce Block"

tail -F ~/java-tron/logs/tron.log | grep "Produce block successfully"
