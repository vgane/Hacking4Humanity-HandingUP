<template>
    <div class="createProfile">
            <form class="form" @submit.prevent=hitSubmit>
                <div class="container">
                    <div class="row">
                        <div class="col">
                            <label for="name">First name</label>
                            <input type="text" class="form-control" placeholder="First name">
                        </div>
                        <div class="col">
                            <label for="name">Last name</label>
                            <input type="text" class="form-control" placeholder="Last name">
                        </div>
                    </div>
                </div>

                <br><br>
                <!--this section is for creating the person's individual story-->
                    <label class="boxTitle">Check all that applies to you (visible to potential donors):</label><br>
                <div class="container formContainer">
                    <div class="row">

                        <div class="col">
                            <div class="form-check">
                                <input class="form-check-input" type="checkbox" value="" id="veteran">
                                <label class="form-check-label" for="defaultCheck1">Veteran</label>
                            </div>
                        </div>

                        <div class="col">
                            <div class="form-check">
                                <input class="form-check-input" type="checkbox" value="" id="domesticViolence">
                                <label class="form-check-label" for="domesticViolence">Domestic Violence Survivor</label>
                            </div>
                        </div>

                        <div class="col">
                            <div class="form-check">
                                <input class="form-check-input" type="checkbox" value="" id="lgbt">
                                <label class="form-check-label" for="lgbt">LGBT</label>
                            </div>
                        </div>

                        <div class="col">
                            <div class="form-check">
                                <input class="form-check-input" type="checkbox" value="" id="minor">
                                <label class="form-check-label" for="minor">Minor</label>
                            </div>
                        </div>

                    </div>
                    <div class="row">
                        <div class="col">
                            <div class="form-check">
                                <input class="form-check-input" type="checkbox" value="" id="mentalIssues">
                                <label class="form-check-label" for="mentalIssues">Mental Issues</label>
                            </div>
                        </div>

                        <div class="col">
                            <div class="form-check">
                                <input class="form-check-input" type="checkbox" value="" id="disabled">
                                <label class="form-check-label" for="disabled">Disabled</label>
                            </div>
                        </div>

                        <div class="col">
                            <div class="form-check">
                                <input class="form-check-input" type="checkbox" value="" id="other">
                                <label class="form-check-label" for="other">Other (please specify in the text box below)</label>
                            </div>
                        </div>

                    </div>

                </div>

                <br><br>
                <!--this section is for identiying a person's specific needs-->
                <label class="boxTitle">Tell us about your specific needs (visible to potential donors):</label><br>
                <div class="container formContainer">
                    <div class="row">
                        <div class="col">
                            <div class="form-check">
                                <input class="form-check-input" type="checkbox" value="" id="housing">
                                <label class="form-check-label" for="housing">Housing</label>
                            </div>
                        </div>

                        <div class="col">
                            <div class="form-check">
                                <input class="form-check-input" type="checkbox" value="" id="nutrition">
                                <label class="form-check-label" for="nutrition">Nutrition</label>
                            </div>
                        </div>

                        <div class="col">
                            <div class="form-check">
                                <input class="form-check-input" type="checkbox" value="" id="health">
                                <label class="form-check-label" for="health">Health Care</label>
                            </div>
                        </div>

                        <div class="col">
                            <div class="form-check">
                                <input class="form-check-input" type="checkbox" value="" id="legal">
                                <label class="form-check-label" for="legal">Legal Advice</label>
                            </div>
                        </div>

                    </div>
                    <div class="row">
                        <div class="col">
                            <div class="form-check">
                                <input class="form-check-input" type="checkbox" value="" id="childcare">
                                <label class="form-check-label" for="childcare">Child Care</label>
                            </div>
                        </div>

                        <div class="col">
                            <div class="form-check">
                                <input class="form-check-input" type="checkbox" value="" id="med">
                                <label class="form-check-label" for="med">Medications</label>
                            </div>
                        </div>

                        <div class="col">
                            <div class="form-check">
                                <input class="form-check-input" type="checkbox" value="" id="other">
                                <label class="form-check-label" for="other">Other (please specify in the text box below)</label>
                            </div>
                        </div>
                    </div>
                </div>

                <br><br>
                <!--this section is for identiying a person's long term goals-->
                <label class="boxTitle">What are your long term goals? (visible to potential donors):</label><br>
                <div class="container formContainer">
                    <div class="row">
                        <div class="col">
                            <div class="form-check-inline">
                                <input class="form-check-input" type="checkbox" value="" id="education">
                                <label class="form-check-label" for="education">Improving my education</label>
                            </div>
                        </div>
                        <div class="col">
                            <div class="form-check">
                                <input class="form-check-input" type="checkbox" value="" id="employment">
                                <label class="form-check-label" for="employment">Employment</label>
                            </div>
                        </div>

                    </div>
                    <div class="row">
                        <div class="col">
                            <div class="form-check">
                                <input class="form-check-input" type="checkbox" value="" id="sober">
                                <label class="form-check-label" for="sober">Getting sober</label>
                            </div>
                        </div>
                        <div class="col">
                            <div class="form-check">
                                <input class="form-check-input" type="checkbox" value="" id="housing">
                                <label class="form-check-label" for="housing">Permanent housing</label>
                            </div>
                        </div>
                        <div class="col">
                            <div class="form-check">
                                <input class="form-check-input" type="checkbox" value="" id="other">
                                <label class="form-check-label" for="other">Other (please specify in the text box below)</label>
                            </div>
                        </div>

                    </div>
                </div>

                <br><br>
                <label class="boxTitle" >Anything else you'd like us to know?</label><br>
                <div class="form-group">
                    <div class="container">
                        <div class="row">
                            <div class="col">
                                <textarea class="form-control" placeholder="Message..." rows="300" id="comment"></textarea>
                            </div>
                        </div>
                    </div>

                </div>

                <button type="submit" value="Submit" class="btn btn-primary">Submit My Application</button>
                
            </form>

        </div>
</template>

<script>
    export default {
        name: "createProfile",
    
        
    methods: {
            hitSubmit(e) {
                e.preventDefault();
                alert(`
               Your information has been successfully submitted!   \n\n
               Name: Gerald \n 
               Summary: I am a disabled veteran with mental health issues. \n 
               My Needs: Healthcare, legal advice, medications \n 
               My Goals: Employment, housing, improving my education \n 
               Additional Information: I have PTSD
                `
                );
            }
        }
        
    }

</script>

<style scoped>

  
    .form{
 border: 25px solid black;
    }
.formContainer{
    border: 3px solid grey;
    background-color:#1F2041;
    color:#ffffff;
}
textarea{
    height: 200px;
      border: 3px solid black;
}
.boxTitle{
    padding-left:90px;
}
button{
    align-content:center;
}
</style>