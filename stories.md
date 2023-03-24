## say goodbye
* goodbye
  - utter_goodbye

## Greeting
* greet
  - utter_greet

## bot challenge
* bot_challenge
  - utter_iamabot

## survey happy path
* ask_catat_kesehatan_harian
    - utter_ask_catat_kesehatan_harian
* affirm
    - health_form
    - form{"name": "health_form"}
    - form{"name": null}
    - utter_slots_values
* thankyou
    - utter_no_worries
    - utter_goodbye

## survey stop
* ask_catat_kesehatan_harian
    - utter_ask_catat_kesehatan_harian
* affirm
    - health_form
    - form{"name": "health_form"}
* out_of_scope
    - utter_ask_continue
* deny
    - action_deactivate_form
    - form{"name": null}
    - utter_goodbye

## survey continue
* ask_catat_kesehatan_harian
    - utter_ask_catat_kesehatan_harian
* affirm
    - health_form
    - form{"name": "health_form"}
* out_of_scope
    - utter_ask_continue
* affirm
    - health_form
    - form{"name": null}
    - utter_slots_values

## no survey
* ask_catat_kesehatan_harian
    - utter_ask_catat_kesehatan_harian
* deny
    - utter_goodbye

## ask pola hidup sehat
* ask_pola_hidup_sehat
    - utter_ask_pola_hidup_sehat

## ask ask pentingnya pola hidup sehat
* ask_pentingnya_pola_hidup_sehat
    - utter_ask_pentingnya_pola_hidup_sehat

## ask waktu tidur
* ask_waktu_tidur
    - utter_ask_waktu_tidur

## makanan sehat
* ask_makanan_sehat
    - utter_ask_makanan_sehat

## makanan yang dihindari
* ask_makanan_yang_dihindari
    - utter_ask_makanan_yang_dihindari

## manfaat olahraga
* ask_manfaat_olahraga
    - utter_ask_manfaat_olahraga

## saran olahraga
* ask_saran_olahraga
    - utter_ask_saran_olahraga

## frekuensi olahraga
* ask_frekuensi_olahraga
    - utter_ask_frekuensi_olahraga

## memulai pola hidup sehat
* ask_memulai_pola_hidup_sehat
    - utter_ask_memulai_pola_hidup_sehat

## motivasi pola hidup sehat
* ask_motivasi_pola_hidup_sehat
    - utter_ask_motivasi_pola_hidup_sehat

## mengurangi stress
* ask_mengurangi_stress
    - utter_ask_mengurangi_stress

## menjaga kesehatan mental
* ask_menjaga_kesehatan_mental
    - utter_ask_menjaga_kesehatan_mental

## insomnia
* ask_insomnia
    - utter_ask_insomnia

## kebiasaan makan buruk
* ask_kebiasaan_makan_buruk
    - utter_ask_kebiasaan_makan_buruk

## cara konsisten
* ask_cara_konsisten
    - utter_ask_cara_konsisten