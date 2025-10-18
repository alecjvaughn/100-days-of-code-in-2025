# #100DaysOfCode Log - Round 1 - Alec Vaughn

The log of my #100DaysOfCode challenge. Started on [October 15, Wednesday, 2025].

## Log

<!--
### R1D0 
Started a Weather App. Worked on the draft layout of the app, struggled with OpenWeather API http://www.example.com
-->

### R1D1
Started 90-day Firebase Free Trial with credits. Tested git features with several commits and one PR. Documented in README [here](https://github.com/alecjvaughn/aleclabs). Attempted Firebase deployment and added DNS records for aleclabs.us to the project. 

Goals: 
1. Deploy a web app with the custom domain aleclabs.us
2. Start a brag document to use for job apps and performance reviews
3. Integrate with LinkedIn Bio
4. Use AI to map qualifications to job post requirements
- ingest job posts and distinguish requirements
- highlight skill gaps and rate match
- allow user to revise and rescore
5. Connect RasPi bot to server for camera and controls

### R1D2
Attempted redeploy [here](https://github.com/alecjvaughn/aleclabs) after successful deploy locally. Build failed with same error and investigated IAM permissions for Cloud Build service.

### R1D3
Successful emulation test and redeploy. Crucial prerequisite was using `npm init @apphosting` and then `firebase init` in the project directory. Process documented in the README for project [here](https://github.com/alecjvaughn/aleclabs)
