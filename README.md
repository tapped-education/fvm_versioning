### Flutter version manager

We are using the fvm (flutter version manager) to ensures that every developer uses the same flutter sdk.
[Go to the repository](https://github.com/leoafarias/fvm)

To install `fvm`:

1. Run `dart pub global activate fvm`
2. Run `fvm --version` to check if the installation was successful.
3. Run `fvm install`. This will install the SDK and link it with the project. This link can be found
   in `.fvm/flutter_sdk`.
4. Run `fvm flutter doctor` to ensure your setup is correct.
5. If needed link the installed SDK with your IDE. See https://fvm.app/docs/getting_started/configuration

⚠️ If you already installed `fvm` but you can not find the `.fvm/flutter_sdk` link to the flutter sdk, you need to
call `fvm install`. You should now see `.fvm/flutter_sdk`.

More details here: https://fvm.app/docs/getting_started/overview

Please ensure that the sdk is set up correctly by calling `fvm flutter doctor`

Ensure that the flutter sdk is not part of the checked in code, by adding the code to `.fvm/flutter_sdk`.
