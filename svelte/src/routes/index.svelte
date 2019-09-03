<script>
    import Section from "components/Section";
    import SubSection from "components/SubSection";
    import Rating from "components/Rating";
</script>

<Section>
    <span slot="title">About Me</span>
    <span slot="content">
        <SubSection>
            <span slot="title">Hobbies</span>
            <span slot="content">
                Something
            </span>
        </SubSection>
        <SubSection>
            <span slot="title">Languages</span>
            <span slot="content">
                Something
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
            <span slot="title">Programming Languages</span>
            <span slot="content">
                C++ <Rating rating={5}/>
            </span>
        </SubSection>
        <SubSection>
            <span slot="title">Frameworks</span>
            <span slot="content">
                Something
            </span>
        </SubSection>
        <SubSection>
            <span slot="title">Tools</span>
            <span slot="content">
                Something
            </span>
        </SubSection>
    </span>
</Section>