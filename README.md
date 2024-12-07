
# Roku App Tutorial

## Step 1: Create a New Directory
Create a new directory by using the following command:

```bash
mkdir {application_name}
```

For this tutorial, I will use:

```bash
mkdir rokuapplication
```

---

## Step 2: Navigate into the Directory
Change into the new directory with:

```bash
cd {application_name}
```

For example:

```bash
cd rokuapplication
```

---

## Step 3: Download the "Hello World" Program
Download the "Hello World" program using:

```bash
wget https://github.com/CalmhostAcct/RokuTutorial/raw/main/hello-world.zip
```

---

## Step 4: Unzip the Downloaded File
Extract the contents of the ZIP file with:

```bash
unzip hello-world.zip
```

---

## Step 5 (Optional): Delete the ZIP File
You can remove the ZIP file after extracting it by using:

```bash
rm hello-world.zip
```

---

## Step 6: Edit the Manifest File
Open the `manifest` file to customize the app's title, version, icon, etc.:

```bash
nano manifest
```

---

## Step 7: Edit the Main Code
Modify how the app behaves by editing the `Main.brs` file:

```bash
cd source
nano Main.brs
```

---

## Step 8: Edit Styling Code
Change how the app looks by editing the `helloworld.xml` file:

```bash
cd components
nano helloworld.xml
```

**Note:** Ensure the folder is correctly named `components` instead of `compenots`.

---

## Step 9: Install Node.js and npm
Install Node.js and npm, which are required for libraries, using:

```bash
sudo apt-get install nodejs npm
```

---

## Step 10: Install `brs`
Install `brs`, which runs BrightScript code:

```bash
npm install -g @rokucommunity/brs
```

---

## Step 11: Install BrighterScript
Install `brighterscript`, which compiles BrightScript code:

```bash
npm install -g brighterscript
```

---

## Step 12 (Optional): Test the Code
Run the BrightScript code to test it by using:

```bash
cd source
brs Main.brs
```

---

## Step 13: Compile the Code
Move to the root directory of your channel and compile the BrightScript code with:

```bash
bsc
```

---

That's it! You have now created and compiled your Roku app.
