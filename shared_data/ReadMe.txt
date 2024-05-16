All the data used in the research were uploaded.
(1)test.csv ----- laboratory variables ----LAB source
(2)test_emr.csv ----- clinical variables ----EMR source
(3)test_ba.csv ----- bone age information ----BA-ratio
(4)test_ba_e.csv ----- bone age information ----BA-image
(5)test_us.csv ----- pelvic ultrasonography ----US source
(6)test_emr_ba.csv ----- LAB + EMR + BA-ratio
(7)test_emr_ba_e.csv ----- LAB + EMR + BA-image
(8)test_us_ba.csv ----- LAB + US + BA-ratio
(9)test_us_ba_e.csv ------ LAB + US + BA-image
(10)test_emr_us.csv ------ LAB + EMR + US
(11)test_emr_ba_us.csv ------ LAB + EMR + BA-ratio + US
(12)test_emr_ba_e_us.csv ------ LAB + EMR + BA-image + US

Variables definition (More details can be seen in the original paper.)
IS_CPP: the label, whether a patient is CPP or not.
LH: luteinizing hormone; 
IGF-1: insulin-like growth factor-1; 
IGFBP-3: IGF-binding protein-3;
FSH: follicle-stimulation hormone; 
PRL: prolactin; GH: growth hormone; 
E2: estradiol; 
BMI: body mass index; 
TTE: testosterone; 
Age_ratio: the ratio of BoneAge to Age;
Imgxxx: extracted features of bone age images;
abnormal: duration of abnormal condition such as breast development;
vulva: tanner stage of vulva development;
pubes: tanner stage of pubic hair;
pigmentation: whether a patient had pigmentation or not;
uterusx(1-3): length of the uterus in three dimensions;
lovaryx(1-3): length of the left ovary in three dimensions;
rovaryx(1-3): length of the right ovary in three dimensions.
