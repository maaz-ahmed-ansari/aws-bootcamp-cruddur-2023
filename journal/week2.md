# Week 2 — Distributed Tracing

## Instrument Honeycomb with OTEL 

- OTEL Environment Variables

![Env Vars](assets/Week-2_Instrument_Honeycomb_Env_Vars.jpg)

- Instrument in app.py

![app.py](assets/Week-2_Instrument_Honeycomb_app.jpg)

- Trace in Honeycomb UI

![Trace](assets/Week-2_Honecomb_traces_1.jpg)

- Instrument **home-activities-mock-data span**

![home-activities-mock-data span](assets/Week-2_Home_activities_trace._and_home-activities-mock-data_spanjpg.jpg)

- home-activities-mock-data span in Honeycomb UI

![Honeycomb UI](assets/Week-2_Honeycomb_Home_activities_trace._and_home-activities-mock-data_spanjpg.jpg)

- Instrument **app.now** and **app.result_length attributes**

![app.now attribute](assets/Week-2_app.now_attribute.jpg)

![app.result_length](assets/Week-2_app.result_length_attribute.jpg)

- **app.now** and **app.result_length** attributes in **Honeycomb UI**

![Honeycomb UI](assets/Week-2_Honeycomb_attributes.jpg)

- **COUNT, MAX and HEATMAP Queries** in Honeycomb

![COUNT](assets/Week-2_Query_count_trace.trace_id.jpg)

![MAX](assets/Week-2_Query_Max_app.result_lengthexists.jpg)

![HEATMAP](assets/Week-2_Query_Heatmap.jpg)

## Instrument AWS X-Ray

- Instrument AWS X-Ray

![Instrument AWS X-Ray](assets/Week-2_Instrument_X-Ray.jpg)

- X-Ray Group, Sampling rule, Traces and Trace Map

![X-Ray Group](assets/Week-2_X-Ray_Group.jpg)

![Sampling rule](assets/Week-2_X-Ray_Sampling_rules.jpg)

![Trace](assets/Week-2_X-Ray_Trace_1jpg.jpg)

![Trace Map](assets/Week-2_trace_map.jpg)

## AWS X-Ray Subsegments

- Instrument AWS X-Ray Subsegments

![Instrument subsegment](assets/Week-2_X-Ray_Subsegment_Instrument.jpg)

![Subsegments](assets/Week-2_X-Ray_Subsegment_UI.jpg)

## Configure custom logger to send to CloudWatch Logs

- Configure CloudWatch logs

![HomeActivities 1](assets/Week-2_CW_logs_HomeActivities_1.jpg)

![HomeActivities 2](assets/Week-2_CW_logs_HomeActivities_2.jpg)

![Console](assets/Week-2_CW_logs.jpg)

## Integrate Rollbar and capture and error

- Instrument Rollbar and Logging in Rollbar UI

![Instrument](assets/Week-2_Instrument_Rollbar.jpg)

![Items](assets/Week-2_Rollbar_Items.jpg)

- Mock Error and Log in UI

![Instrument](assets/Week-2_Rollbar_Error.jpg)

![Error](assets/Week-2_Rollbar_Error_UI.jpg)

![Detailed Error](assets/Week-2_Rollbar_Error_UI_Details.jpg)
