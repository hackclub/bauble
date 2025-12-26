<svelte:head>
    <link rel="icon" type="image/png" href="/square.png" />
</svelte:head>

<a href="https://hackclub.com" target="_blank" rel="noopener noreferrer" class="fixed top-0 left-0 z-50">
    <img src="https://assets.hackclub.com/flag-orpheus-left.png" alt="Hack Club" class="w-50"/>
    
</a>
 
<section class="min-h-screen flex flex-col items-center justify-center">
    <img src="logo.png" alt="Bauble Logo" class="w-200 object-center" />
    <h2 class="font-bubblegum text-3xl pb-10 text-white text-center">
        3D model an ornament, get it printed and put on the HQ tree! Ends December 25th.
    </h2>  
    <div class="flex gap-25 mt-5">
        <button class="font-bubblegum bg-white text-black text-3xl py-6 px-18 rounded-lg transition cursor-pointer" on:click={() => document.getElementById('faq').scrollIntoView({ behavior: 'smooth' })}>FAQ</button>
        <a href="https://hackclub.com" target="_blank" rel="noopener noreferrer" class="font-bubblegum bg-white text-black text-3xl py-6 px-18 rounded-lg transition">Submissions Closed!</a>
    </div>
</section>

<div class="flex flex-col items-center justify-center min-h-screen px-10" id="faq"> 
    <div class="w-full max-w-2xl px-4">
        <h2 class="font-bubblegum text-5xl text-white text-center pb-5">FAQs</h2>
        <details class="mb-3 bg-white rounded-lg">
            <summary class="font-bubblegum text-xl text-black p-4 cursor-pointer">What is Bauble?</summary>
            <p class="font-bubblegum px-4 pb-4 text-black">Bauble is a Hack Club YSWS program where you 3D model an ornament, and you get it printed out put on Oscar, the tree at Hack Club’s HQ in Vermont! After the tree gets taken down, you'll receive your ornament in the mail!</p>
        </details>
        <details class="mb-3 bg-white rounded-lg">
            <summary class="font-bubblegum text-xl text-black p-4 cursor-pointer">How do I participate?</summary>
            <p class="font-bubblegum px-4 pb-4 text-black">Design a 3D model of an ornament! It can be whatever you want, as long as it’s appropriate and is under 100 x 100 x 100 mm. You have to make it yourself, models downloaded off of the internet are not allowed.</p>
        </details>
        <details class="mb-3 bg-white rounded-lg">
            <summary class="font-bubblegum text-xl text-black p-4 cursor-pointer">Do I need to track time with Lapse/Hackatime?</summary>
            <p class="font-bubblegum px-4 pb-4 text-black">Time tracking is not required. You may track time with Lapse if you wish, but it is not necessary.</p>
        </details>
        <details class="mb-3 bg-white rounded-lg">
            <summary class="font-bubblegum text-xl text-black p-4 cursor-pointer">What are the requirements?</summary>
            <p class="font-bubblegum px-4 pb-4 text-black">Your ornament must:</p>
            <ul class="font-bubblegum px-4 pb-4 text-black list-disc ml-8">
                <li>Be modeled by you;</li>
                <li>Be in STL format;</li>
                <li>Be uploaded to Printables;</li>
                <li>Have a hole of a minimum 5mm diameter or some other way a hook or string could be attached;</li>
                <li>Be no larger than 100 x 100 x 100 mm in all directions;</li>
                <li>Be appropriate, and;</li>
                <li>Be able to print without supports.</li>
            </ul>
            <p class="font-bubblegum px-4 pb-4 text-black">If you have any other questions about requirements, ask in the <a href="https://app.slack.com/client/E09V59WQY1E/C0A1SH6PF89" target="_blank" rel="noopener noreferrer" class="underline cursor-pointer">#bauble</a> channel in the Slack!</p>
        </details>
        <details class="mb-3 bg-white rounded-lg">
            <summary class="font-bubblegum text-xl text-black p-4 cursor-pointer">How will I receive my ornament?</summary>
            <p class="font-bubblegum px-4 pb-4 text-black">After the tree is taken down, your ornament will be packaged up and shipped out to you from HQ!</p>
        </details>
        <details class="mb-3 bg-white rounded-lg">
            <summary class="font-bubblegum text-xl text-black p-4 cursor-pointer">Is this double dippable?</summary>
            <p class="font-bubblegum px-4 pb-4 text-black">No, Bauble cannot be double dipped with any other Hack Club programs.</p>
        </details>
        <details class="mb-3 bg-white rounded-lg">
            <summary class="font-bubblegum text-xl text-black p-4 cursor-pointer">I've finished my ornament!</summary>
            <p class="font-bubblegum px-4 pb-4 text-black">Great! Make sure it follows all the requirements (see the requirements section above), upload it to Printables, and <a href="https://hackclub.com" target="_blank" rel="noopener noreferrer" class="underline cursor-pointer">submit</a>!</p>
        </details>
        <details class="mb-3 bg-white rounded-lg">
            <summary class="font-bubblegum text-xl text-black p-4 cursor-pointer">I have some other questions!</summary>
            <p class="font-bubblegum px-4 pb-4 text-black">Ask in the <a href="https://app.slack.com/client/E09V59WQY1E/C0A1SH6PF89" target="_blank" rel="noopener noreferrer" class="underline cursor-pointer">#bauble</a> channel in the Slack!</p>
        </details>
    </div>
</div>
