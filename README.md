
<!---
dbullPSU/dbullPSU is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

go to plutus-pioneer-program/code/weekxx/
less cabal.project and copy correct tag for plutus-apps.git 
go to plutus-apps/
git checkout tagxxxxxxxxxxxxx
run: nix-shell
once in  nix shell, cd plutus-pioneer-program/code/weekxx/
run: cabal build

*from plutus-pioneer-program/code/weekxx/ can run cabal repl


*For haskell help, go to ~/plutus-apps/ and run: build-and-serve-docs	http://0.0.0.0:8002/




To run playground, open 2nd terminal:
2ndTerminal: cd plutus-apps/  
2ndTerminal: run nix-shell
1stTerminal: from ~/plutus-apps/: cd plutus-playground-client
1stTerminal: run plutus-playground-server
2ndTerminal: from ~/plutus-apps/: cd plutus-playground-client
2ndTerminal: npm start     builds playground at https://localhost:8009/
localhost:8009:  delete sample code
localhost:8009:  paste in auction code
localhost:8009:  delete the module header and then compile code
