<script>
    import Section from "components/Section";
    import SubSection from "components/SubSection";
    import Rating from "components/Rating";
</script>

<style type="text/scss">
    a {
        text-decoration: none;
        color: #ff8000;
    }
</style>

<Section>
    <span slot="title">About Me</span>
    <span slot="text">
        I currently study Computer Science at the Technical University of Denmark (DTU).
        I work as a student helper at Siemens where I'm working on a variety of projects, but I typically make websites.
    </span>
    <span slot="content">
        <SubSection>
            <span slot="title">Hobbies</span>
            <span slot="content">
                I enjoy working out and working on my peronal
                <a href="https://github.com/NikRadi">projects</a>.
                My projects typically have an AI-theme, and may vary from
                <a href="https://github.com/NikRadi/Kasparov2">chess bots</a>
                to simple
                <a href="https://github.com/NikRadi/SimpleNeuralNetPy">deep learning</a> projects.
                If I have any time left during the day I usually play the piano.
            </span>
        </SubSection>
        <SubSection>
            <span slot="title">Languages</span>
            <span slot="content">
                My native language is Farsi, but since I live in Denmark I mainly speak Danish. I also know English and a tiny bit German.
            </span>
        </SubSection>
    </span>
</Section>
<Section>
    <span slot="title">Experiences</span>
    <span slot="content">
        <SubSection>
            <span slot="title">Education</span>
            <span slot="content">
                Something
            </span>
        </SubSection>
        <SubSection>
            <span slot="title">Career</span>
            <span slot="content">
                Something
            </span>
        </SubSection>
        <SubSection>
            <span slot="title">Projects</span>
            <span slot="content">
                Something
            </span>
        </SubSection>
    </span>
</Section>
<Section>
    <span slot="title">Skills</span>
    <span slot="content">
        <SubSection>
            <span slot="title">Programming, Scripting and Markup Languages</span>
            <span slot="content">
                <Rating rating={5}>c++</Rating>
                <Rating rating={5}>C#</Rating>
                <Rating rating={5}>Python</Rating>
                <Rating rating={4}>HTML / CSS</Rating>
                <Rating rating={3}>SASS / SCSS</Rating>
                <Rating rating={3}>c</Rating>
                <Rating rating={3}>Java</Rating>
                <Rating rating={3}>SQL</Rating>
                <Rating rating={3}>VBA</Rating>
                <Rating rating={2}>Javascript</Rating>
                <Rating rating={2}>Prolog</Rating>
                <Rating rating={1}>F#</Rating>
                <Rating rating={1}>R</Rating>
            </span>
        </SubSection>
        <SubSection>
            <span slot="title">Frameworks</span>
            <span slot="content">
                <Rating rating={4}>Flask</Rating>
                <Rating rating={4}>Svelte</Rating>
            </span>
        </SubSection>
        <SubSection>
            <span slot="title">Tools</span>
            <span slot="content">
                <Rating rating={4}>Git</Rating>
                <Rating rating={3}>SQLite</Rating>
                <Rating rating={2}>PostgresSQL</Rating>
            </span>
        </SubSection>
    </span>
</Section>