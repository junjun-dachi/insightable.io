# insightable-website

This project is the public landing page for Insightable. If you download the packaged app, use it like this:

## After you download

1. Unzip the downloaded archive into a folder on your computer.
2. Open the extracted folder and launch the app:
   - macOS: run ./start.sh
   - Windows: double-click start.cmd or run it from Command Prompt
3. A browser window should open at http://localhost:3000. If it does not, open that address manually.
4. On the first launch, the app will create its data, config, and log folders automatically, copy the example settings, and generate a local encryption key.
5. When you are finished, stop the app with ./stop.sh on macOS or stop.cmd on Windows.

## Notes

- No separate Java or Node installation is required for the downloaded package.
- If you are building the package yourself, refer to the upstream build scripts documentation for the packaging workflow.